# Stability AI GraphQL Schema

## Overview

This conceptual GraphQL schema represents the Stability AI developer platform, which provides generative AI APIs for image generation, image editing, image upscaling, video generation, audio generation, and 3D asset creation. The schema is derived from the Stability AI REST API documented at https://platform.stability.ai/docs/api-reference.

Stability AI's platform is built around the Stable Diffusion family of models, including SD3, SDXL, Stable Image Ultra, Stable Video Diffusion, and Stable Audio. All operations are authenticated via bearer token (API key) and priced in credits.

## Schema File

- [stability-ai-schema.graphql](stability-ai-schema.graphql)

## Type Categories

### Engine and Model Types

These types represent the inference engines and models available on the platform.

| Type | Description |
|------|-------------|
| `Engine` | A single Stability AI inference engine/model |
| `EngineID` | Unique string identifier for an engine |
| `EngineDetails` | Metadata including version, resolution limits, and defaults |
| `EngineCapabilities` | Supported operations and constraints for an engine |
| `StableDiffusion` | Base Stable Diffusion model configuration |
| `SDXL` | Stable Diffusion XL model with optional refiner |
| `SD3` | Stable Diffusion 3 and 3.5 model family |
| `StableVideo` | Stable Video Diffusion model configuration |
| `AuroraModel` | Aurora generative model |
| `StableAudio` | Stable Audio generation model |

### Prompt Types

These types represent the text inputs that drive generation.

| Type | Description |
|------|-------------|
| `TextPrompt` | A positive text prompt with optional weight |
| `NegativePrompt` | A negative prompt specifying what to avoid |
| `PromptWeight` | Relative weighting value for a prompt |
| `TextWeight` | Text guidance weight with min/max bounds |

### Generation Parameter Types

These types capture the configurable parameters for generation operations.

| Type | Description |
|------|-------------|
| `CFGScale` | Classifier-free guidance scale |
| `Steps` | Number of diffusion steps |
| `Seed` | Random seed for reproducible results |
| `Width` | Image width in pixels |
| `Height` | Image height in pixels |
| `ImageSize` | Combined width and height |
| `AspectRatio` | Predefined aspect ratio enum |
| `StyleGuidance` | Strength of style application |
| `ImageStrength` | Influence of init image in img2img |
| `MotionBucketID` | Video motion intensity setting |
| `MotionBucketRange` | Allowed range for motion bucket values |
| `FPS` | Frames per second for video |

### Image Types

These types represent image inputs and outputs.

| Type | Description |
|------|-------------|
| `Artifact` | Raw or encoded image/media artifact |
| `GeneratedImage` | A generated output image with metadata |
| `OutputImage` | Resolved output image with full metadata |
| `InitImage` | Input initialization image for img2img workflows |
| `MaskImage` | Mask image for inpainting/outpainting |
| `Base64Image` | Scalar type for base64-encoded image data |

### Generation Operation Types

These types represent the core generation workflows.

| Type | Description |
|------|-------------|
| `TextToImage` | Text-to-image generation operation |
| `ImageToImage` | Image-to-image generation operation |
| `Inpainting` | Fills masked regions of an image |
| `Outpainting` | Extends image boundaries |
| `Upscale` | AI-powered resolution upscaling |
| `ControlNet` | ControlNet-guided structural generation |
| `Generation` | A complete generation job with status |
| `GenerationResult` | Output payload from any generation operation |

### Video Generation Types

| Type | Description |
|------|-------------|
| `VideoGeneration` | A video generation job |
| `VideoFrame` | A single frame within a generated video |
| `VideoOutput` | Output of a completed video generation job |

### Audio Generation Types

| Type | Description |
|------|-------------|
| `AudioGeneration` | An audio generation job |
| `AudioOutput` | Output of a completed audio generation job |

### Account and Access Types

| Type | Description |
|------|-------------|
| `APIKey` | API key credential for authentication |
| `UsageMetrics` | Account usage statistics |
| `Credits` | Credit balance and transaction data |
| `RateLimit` | Current rate limit state and configuration |
| `WebhookEvent` | Platform event delivered via webhook |
| `Tool` | Available API endpoint descriptor |

## Enums

| Enum | Values |
|------|--------|
| `ImageFormat` | JPEG, PNG, WEBP |
| `ArtifactType` | IMAGE, VIDEO, AUDIO, MASK |
| `FinishReason` | SUCCESS, ERROR, CONTENT_FILTERED |
| `MaskSource` | MASK_IMAGE_WHITE, MASK_IMAGE_BLACK, INIT_IMAGE_ALPHA |
| `StylePreset` | 17 style presets including PHOTOGRAPHIC, ANIME, CINEMATIC, etc. |
| `Sampler` | 10 diffusion samplers including DDIM, K_EULER, K_DPM_2, etc. |
| `AspectRatio` | 7 ratios including 1:1, 16:9, 4:3, 21:9 |
| `EngineCapabilityType` | TEXT_TO_IMAGE, IMAGE_TO_IMAGE, INPAINTING, OUTPAINTING, UPSCALE, CONTROL, VIDEO, AUDIO, THREE_D |

## Root Operations

### Query

- `engines` — List all available inference engines
- `engine(id)` — Get a specific engine by ID
- `usageMetrics` — Current account usage statistics
- `credits` — Current credit balance
- `rateLimit` — Current rate limit state
- `generation(id)` — Retrieve a generation job by ID
- `videoGeneration(id)` — Retrieve a video generation job by ID
- `audioGeneration(id)` — Retrieve an audio generation job by ID
- `tools` — List available API tools

### Mutation

- `textToImage` — Run a text-to-image generation
- `imageToImage` — Run an image-to-image generation
- `inpaint` — Fill masked regions of an image
- `outpaint` — Extend image boundaries
- `upscale` — AI upscale an image
- `controlNet` — ControlNet-guided generation
- `generateVideo` — Start a video generation job
- `generateAudio` — Start an audio generation job

## Key Platform Details

- **Base URL**: https://api.stability.ai
- **Authentication**: Bearer token (API key)
- **Credits**: 1 credit = $0.01 USD
- **Rate Limits**: 150 requests per 10 seconds per key; 10 concurrent image jobs; 5 concurrent video jobs
- **Models**: Stable Image Ultra (SD3.5 Large), Stable Image Core, SD3, SDXL, Stable Video Diffusion, Stable Audio
- **Open Weights**: Core models available under open weights license for research and community use

## References

- API Reference: https://platform.stability.ai/docs/api-reference
- Getting Started: https://platform.stability.ai/docs/getting-started
- GitHub: https://github.com/Stability-AI
- Pricing: https://stability.ai/api-pricing-update-25
