# Changelog

## 0.2.0

* Updated: Compatible with Appwrite server `1.9.x`
* Added: Multi-file project configuration via `includes` in `appwrite.config.json`
* Added: Explicit account switching with `appwrite login --switch`
* Added: Flag-based list query helpers (`--where`, `--sort-desc`, `--limit`, `--cursor-after`, `--select`, `--json`)
* Added: Webhook management (`appwrite webhooks`, `appwrite pull/push webhooks`)
* Added: `.env`-based function and site variables workflow with `--with-variables`
* Added: Project management commands (services, protocols, OAuth providers, mock phones, ephemeral keys)
* Added: Deployment activation flag (`--activate=false`) for staged rollouts
* Added: `appwrite update` and `appwrite completion install` maintenance commands
* Updated: Function and site config fields use `buildSpecification`, `runtimeSpecification`, `deploymentRetention`, `scopes`, `ignore`
* Updated: Homebrew install now uses `appwrite/appwrite` tap
* Updated: Cloud account login normalized to `https://cloud.appwrite.io/v1`

## 0.1.0

Initial release compatible with Appwrite server 1.8.x. Follows the [Agent Skills Open Standard](https://agentskills.io/home).

- Added agent skills for 9 languages: TypeScript, Python, PHP, Go, Kotlin, Swift, Ruby, .NET, and Dart
- Coverage for Account, Users, TablesDB, Storage, Teams, Functions, and Realtime services
- Query builder with filtering, sorting, pagination, and field selection
- Permission and Role helpers for access control
- SSR authentication patterns for major frameworks
- Consistent error handling via `AppwriteException` across all languages