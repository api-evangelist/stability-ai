# Stability AI

Stability AI is an AI company that develops open-source generative AI models for image, audio, video, and language, including the Stable Diffusion family of image generation models. The Stability AI developer platform provides REST APIs for text-to-image generation, image editing, image upscaling, image structure control, video generation, and 3D asset creation. All APIs are accessible at api.stability.ai using bearer token authentication.

**URL:** [https://platform.stability.ai](https://platform.stability.ai)

## Tags

3D Generation, AI, Generative AI, Image Generation, Image Editing, Machine Learning, Stable Diffusion, Text to Image, Video Generation

## APIs

### Stability AI Stable Image Generate API

The Stability AI Stable Image Generate API provides text-to-image generation capabilities powered by models including Stable Diffusion 3.5 and Stable Image Ultra. Developers can generate high-quality images from text prompts with control over style, dimensions, and output format.

**Human URL:** [https://platform.stability.ai/docs/getting-started/stable-image](https://platform.stability.ai/docs/getting-started/stable-image)

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-generate-openapi.yml)

### Stability AI Stable Image Edit API

The Stability AI Stable Image Edit API provides image editing capabilities including inpainting, outpainting, object erasing, background removal, search-and-replace, search-and-recolor, and replace-background-and-relight functionality.

**Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-edit-openapi.yml)

### Stability AI Stable Image Upscale API

The Stability AI Stable Image Upscale API enables developers to increase the resolution of images using AI-powered upscaling models. Supports conservative and creative upscaling modes.

**Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-upscale-openapi.yml)

### Stability AI Stable Image Control API

The Stability AI Stable Image Control API provides image-to-image generation guided by structural inputs such as sketches and reference structures using ControlNet-based models.

**Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-control-openapi.yml)

### Stability AI Stable Video Diffusion API

The Stability AI Stable Video Diffusion API enables developers to generate short video clips from a single input image using the Stable Video Diffusion model.

**Human URL:** [https://platform.stability.ai/docs/getting-started/stable-video](https://platform.stability.ai/docs/getting-started/stable-video)

#### Properties

- [Documentation](https://platform.stability.ai/docs/getting-started/stable-video-diffusion)
- [OpenAPI](openapi/stability-ai-stable-video-diffusion-openapi.yml)

### Stability AI Stable Fast 3D API

The Stability AI Stable Fast 3D API generates textured 3D mesh assets from single input images for use in games, AR, VR, and product visualization.

**Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-fast-3d-openapi.yml)

## Common Properties

- [Portal](https://platform.stability.ai)
- [Documentation](https://platform.stability.ai/docs/getting-started)
- [Website](https://stability.ai)
- [Pricing](https://stability.ai/api-pricing-update-25)
- [Terms of Service](https://stability.ai/terms-of-service)
- [Privacy Policy](https://stability.ai/privacy-policy)
- [GitHub Org](https://github.com/stability-ai)
- [JSON-LD](json-ld/stability-ai-context.jsonld)
- [JSON Schema](json-schema/stability-ai-image-generation-schema.json)
- [JSON Structure](json-structure/stability-ai-image-generation-structure.json)
- [Vocabulary](vocabulary/stability-ai-vocabulary.yml)
- [Spectral Rules](rules/stability-ai-rules.yml)

## Capabilities

### Shared Definitions (`capabilities/shared/`)

| File | Description |
|------|-------------|
| [stable-image-generate.yaml](capabilities/shared/stable-image-generate.yaml) | Stable Image Generate — text-to-image via Ultra, Core, and SD3 models (3 operations) |
| [stable-image-edit.yaml](capabilities/shared/stable-image-edit.yaml) | Stable Image Edit — inpainting, outpainting, erase, search-and-replace, search-and-recolor, background removal, background replacement (7 operations) |

### Workflow Capabilities

| File | Description |
|------|-------------|
| [image-creation.yaml](capabilities/image-creation.yaml) | Stability AI Image Creation — unified workflow combining generation and editing APIs (9 REST paths, 11 MCP tools) |
