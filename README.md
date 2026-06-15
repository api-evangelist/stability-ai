# Stability AI (stability-ai)

Stability AI is an AI company that develops open-source generative AI models for image, audio, video, and language, including the Stable Diffusion family of image generation models. The Stability AI developer platform provides REST APIs for text-to-image generation, image editing, image upscaling, image structure control, video generation, and 3D asset creation. All APIs are accessible at api.stability.ai using bearer token authentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stability-ai/refs/heads/main/apis.yml)

## Tags

- 3D Generation
- AI
- Generative AI
- Image Generation
- Image Editing
- Machine Learning
- Stable Diffusion
- Text to Image
- Video Generation

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-19

## APIs

### Stability AI Stable Image Generate API

The Stability AI Stable Image Generate API provides text-to-image generation capabilities powered by models including Stable Diffusion 3.5 and Stable Image Ultra. Developers can generate high-quality images from text prompts with control over style, dimensions, and output format. The API supports multiple model tiers including Stable Image Core for fast and affordable generation and Stable Image Ultra for state-of-the-art quality results.

- **Human URL:** [https://platform.stability.ai/docs/getting-started/stable-image](https://platform.stability.ai/docs/getting-started/stable-image)
- **Base URL:** `https://api.stability.ai`

#### Tags

- Generative AI
- Image Generation
- Stable Diffusion
- Text to Image

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-generate-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stability-ai-stable-image-generate.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stability-ai-stable-image-generate.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stability AI Stable Image Edit API

The Stability AI Stable Image Edit API provides image editing capabilities including inpainting, outpainting, object erasing, background removal, and search-and-replace functionality. Developers can use natural language prompts to modify existing images, fill in masked regions, extend image boundaries, or replace specific objects within a scene.

- **Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)
- **Base URL:** `https://api.stability.ai`

#### Tags

- Generative AI
- Image Editing
- Inpainting
- Outpainting
- Search and Replace

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-edit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stability-ai-stable-image-edit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stability-ai-stable-image-edit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stability AI Stable Image Upscale API

The Stability AI Stable Image Upscale API enables developers to increase the resolution of images using AI-powered upscaling models. The API offers both conservative upscaling, which preserves the original image closely while increasing resolution, and creative upscaling, which enhances and adds detail to images during the upscaling process.

- **Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)
- **Base URL:** `https://api.stability.ai`

#### Tags

- Generative AI
- Image Enhancement
- Image Upscaling
- Super Resolution

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-upscale-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stability-ai-stable-image-upscale.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stability-ai-stable-image-upscale.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stability AI Stable Image Control API

The Stability AI Stable Image Control API provides image-to-image generation guided by structural inputs such as sketches and reference structures. Using ControlNet-based models, developers can generate new images that follow the composition, edges, or layout of a source image while applying new styles or content based on text prompts.

- **Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)
- **Base URL:** `https://api.stability.ai`

#### Tags

- ControlNet
- Generative AI
- Image Generation
- Image to Image

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-image-control-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stability-ai-stable-image-control.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stability-ai-stable-image-control.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stability AI Stable Video Diffusion API

The Stability AI Stable Video Diffusion API enables developers to generate short video clips from a single input image. Powered by the Stable Video Diffusion model, the API produces smooth animated sequences that bring static images to life with realistic motion.

- **Human URL:** [https://platform.stability.ai/docs/getting-started/stable-video](https://platform.stability.ai/docs/getting-started/stable-video)
- **Base URL:** `https://api.stability.ai`

#### Tags

- Generative AI
- Image to Video
- Stable Diffusion
- Video Generation

#### Properties

- [Documentation](https://platform.stability.ai/docs/getting-started/stable-video-diffusion)
- [OpenAPI](openapi/stability-ai-stable-video-diffusion-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stability-ai-stable-video-diffusion.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stability-ai-stable-video-diffusion.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Stability AI Stable Fast 3D API

The Stability AI Stable Fast 3D API generates textured 3D mesh assets from single input images. The API rapidly produces 3D models suitable for use in games, augmented reality, virtual reality, and product visualization workflows.

- **Human URL:** [https://platform.stability.ai/docs/api-reference](https://platform.stability.ai/docs/api-reference)
- **Base URL:** `https://api.stability.ai`

#### Tags

- 3D Generation
- Generative AI
- Image to 3D
- Mesh Generation

#### Properties

- [Documentation](https://platform.stability.ai/docs/api-reference)
- [OpenAPI](openapi/stability-ai-stable-fast-3d-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/stability-ai-stable-fast-3d.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stability-ai-stable-fast-3d.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/stability-ai)
- [Website](https://stability.ai)
- [Documentation](https://platform.stability.ai/docs/getting-started)
- [Portal](https://platform.stability.ai)
- [Pricing](https://stability.ai/api-pricing-update-25)
- [Terms of Service](https://stability.ai/terms-of-service)
- [Privacy Policy](https://stability.ai/privacy-policy)
- [Git Hub  Org](https://github.com/stability-ai)
- [JSON-LD](json-ld/stability-ai-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/stability-ai-image-generation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/stability-ai-image-generation-structure.json)
- [Vocabulary](vocabulary/stability-ai-vocabulary.yml)
- [Spectral Rules](rules/stability-ai-rules.yml)
- [Features](undefined)
- [Integrations](https://stability.ai/partners)
