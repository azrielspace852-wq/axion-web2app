# Edit Core Config

Opens an app's **type-specific** settings — its source and runtime configuration. Tap ⋮ on an app card, then **Edit Core Config**. Each app type has a different core config; every type page documents its own in a detailed **Core config** section.

## What it edits

The type-specific creation form, reused as an editor. Follow each link to the full, sub-categorized field reference:

| App type | Core config covers |
| --- | --- |
| [Web](/zh/guide/app-types/web) | Target & engine, user agent & display, injection, popups *(Web has a single combined editor — see note)* |
| [Multi-Web](/zh/guide/app-types/multi-web) | Sites (name/URL/type/icon/theme/selectors), layout & display, refresh, shared injection |
| [HTML](/zh/guide/app-types/html) | Source, entry file, load mode & port, capabilities, appearance |
| [Offline Pack](/zh/guide/app-types/offline-pack) | Crawl scope, filtering, network |
| [Frontend](/zh/guide/app-types/frontend) | Build output, framework, toolchain |
| [PHP](/zh/guide/app-types/php) | Project, server (port/env), dependencies & extensions |
| [WordPress](/zh/guide/app-types/wordpress) | Site, admin account, theme & plugins, source & install, server |
| [Node.js](/zh/guide/app-types/nodejs) | Project, build mode, server (entry/port/env), native addons |
| [Python](/zh/guide/app-types/python) | Project, entry & server, dependencies & extensions |
| [Go](/zh/guide/app-types/go) | Project, build (binary/arch), server (port/static/env) |
| [Media](/zh/guide/app-types/media) | Source, playback, display |
| [Gallery](/zh/guide/app-types/gallery) | Content, playback, view, display |

## Notes

- **Web apps don't show this entry** — they have a single **Edit** that covers everything, since web config isn't split.
- For the shared options (appearance, networking, privacy, export), use [Edit Common Config](/zh/guide/app-actions/edit-common-config/).