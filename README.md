# Dart · Mobile module foundation

Reusable presentation package skeleton for separate dart mobile application with a flutter host for ios and android. The public entry exports registration metadata only. There are no screens, API operations or implemented domain behaviors yet. Framework peers identify the intended adapter family; they do not prove integration compatibility.

## Develop and verify

```bash
flutter pub get
flutter analyze
# Review pubspec publishing metadata and remove publish_to: none only for an authorized release.
dart pub publish --dry-run
```

Keep application roots separate from this package. Add capability-specific presentation, DTO mapping and injected transport interfaces through explicit exports. Keep navigation/session integration in the host adapter, and keep secrets and authoritative domain behavior in Laravel. Do not invent API routes or import application aliases into a reusable package.

Start capability modules from this foundation, change package/repository identities, link their canonical scope and validate a packed artifact in a clean consumer before an authorized registry release. Repository creation does not publish to npm or pub.dev.

See the [presentation guide](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/DART.md), [module architecture](https://github.com/liberusoftware/documentation/blob/main/architecture/MODULES.md), and [source inventory](https://github.com/liberusoftware/documentation/blob/main/architecture/SOURCE-INVENTORY.md). Use the matching project-boilerplate application to compose a real consumer; packages and deployed applications have separate release lifecycles.
