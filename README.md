# Stability AI (stability-ai)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
