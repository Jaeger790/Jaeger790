# Repository review

Reviewed October 17, 2026. This index groups public repositories by purpose. It is a repository and targeted code review, not a full security audit or proof that every application runs.

## Review status

Cleanup PRs are reviewable changes. Until merged, their README, source and file cleanup changes are not on the default branch. Repository names, visibility and archive settings are unchanged. Private project details are not included here.

| Repository | Type | Findings and validation | Changes |
| --- | --- | --- | --- |
| [InventoryManagement](https://github.com/Jaeger790/InventoryManagement) | Desktop app | Default branch was missing source; restoration and tests are in PR #1. | [Review PR](https://github.com/Jaeger790/InventoryManagement/pull/1) |
| [Northstar-Scheduling](https://github.com/Jaeger790/Northstar-Scheduling) | Desktop app | Default branch was missing source; restoration and tests are in PR #1. | [Review PR](https://github.com/Jaeger790/Northstar-Scheduling/pull/1) |
| [bntcandles](https://github.com/Jaeger790/bntcandles) | Desktop app | Qt/MySQL app; build paths and external configuration corrected. Full build not verified. | [Review PR](https://github.com/Jaeger790/bntcandles/pull/1) |
| [ClassTracker](https://github.com/Jaeger790/ClassTracker) | Mobile coursework | Android/Room app; remove local build state and release artifacts. Android build not verified. | [Review PR](https://github.com/Jaeger790/ClassTracker/pull/2) |
| [Labs](https://github.com/Jaeger790/Labs) | Exercises and automation | Add navigation and remove rebuildable output. Preserve and identify examples missing source. | [Review PR](https://github.com/Jaeger790/Labs/pull/1) |
| [OBDII](https://github.com/Jaeger790/OBDII) | Hardware prototype | Configure adapter port and remove duplicate Qt event loop. Hardware testing pending. | [Review PR](https://github.com/Jaeger790/OBDII/pull/1) |
| [shutdownTimer](https://github.com/Jaeger790/shutdownTimer) | Windows utility | Add a C# project and valid console entry point. GitHub Windows compilation passed. | [Review PR](https://github.com/Jaeger790/shutdownTimer/pull/1) |
| [DiscordBot](https://github.com/Jaeger790/DiscordBot) | API prototype | Add startup, environment config and nonblocking timed requests. Live APIs not tested. | [Review PR](https://github.com/Jaeger790/DiscordBot/pull/1) |
| [stockTracker](https://github.com/Jaeger790/stockTracker) | API experiment | Use configurable API access and real JSON output. Provider access not tested. | [Review PR](https://github.com/Jaeger790/stockTracker/pull/1) |
| [xmaslist](https://github.com/Jaeger790/xmaslist) | Web utility | Document setup and reference a managed database in Render. Deployment and runtime gaps remain. | [Review PR](https://github.com/Jaeger790/xmaslist/pull/1) |
| [kreigercode.github.io](https://github.com/Jaeger790/kreigercode.github.io) | Earlier portfolio | Fix project links and accumulating menu listeners. Live visual testing pending. | [Review PR](https://github.com/Jaeger790/kreigercode.github.io/pull/1) |
| [StudentRoster](https://github.com/Jaeger790/StudentRoster) | C++ coursework | Fix deletion ownership/capacity and remove generated output. Compile and sanitizer regression passed. | [Review PR](https://github.com/Jaeger790/StudentRoster/pull/1) |
| [SQL](https://github.com/Jaeger790/SQL) | Database coursework | Separate SQL Server/PostgreSQL scripts from generated output. Scripts not executed. | [Review PR](https://github.com/Jaeger790/SQL/pull/1) |
| [crypto](https://github.com/Jaeger790/crypto) | Asset only | Contains an image, with no application source or build. | README updated |
| [token-list](https://github.com/Jaeger790/token-list) | Upstream fork | Keep upstream data, license and README; add fork context. | [Review PR](https://github.com/Jaeger790/token-list/pull/1) |
| [WebsiteTemplates](https://github.com/Jaeger790/WebsiteTemplates) | Placeholder | Was empty; README now identifies its intended scope. | README updated |
| [Jaeger790](https://github.com/Jaeger790/Jaeger790) | Profile navigation | Categorized public project index and this review record. | README updated |

## Organization rules

- Keep each application in its own repository.
- Put small exercises and workstation scripts in Labs, with a README per runnable tool.
- Keep generated output, editor state, local settings and secrets out of source control. Preserve the Maven/Gradle wrapper files required to build.
- Keep source-less examples clearly identified instead of deleting their only remaining artifacts.
- Mark prototypes and missing build/schema files directly. Describe verified behavior and record what still needs testing.
- Keep the upstream fork separate from original work.
