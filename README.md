# Video and Audio Filament

Registers the tenant-aware `MediaAssetResource` with the application admin resource registry. Forms and tables are presentation adapters; lifecycle and transcoding rules remain in the domain service.

<!-- module-presentation-guide:begin -->
## Presentation architecture and project hosts

- Capability/source key: `liberusoftware/module-cms-video-and-audio`.
- Actual Composer identity: `liberusoftware/module-cms-video-and-audio-filament`.
- [Filament capability plan](https://github.com/liberusoftware/documentation/blob/main/projects/cms/filament/video-and-audio.md) · [Filament standard](https://github.com/liberusoftware/documentation/blob/main/standards/FILAMENT.md) · [Module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md).

The application owns panel composition, routing, session integration and deployment. This module owns its focused presentation and delegates domain behavior to reviewed public owner contracts. Keep host App aliases, duplicate records and client-only authorization outside reusable package boundaries.

Documented consumer project families:

- [CMS](https://github.com/liberusoftware/project-cms-laravel-filament): Content authoring, publishing and delivery.

Other web, mobile and desktop presentations are listed in the [project catalog](https://github.com/liberusoftware/documentation/blob/main/projects/REPOSITORIES.md). Those skeletons provide starting structures; links do not establish feature parity, compatible releases or completed device/API integrations. Independent presentation packages keep their own Composer, npm or pub metadata.
<!-- module-presentation-guide:end -->
