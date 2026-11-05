# Accountant Workspace · Dart · Mobile

Independent presentation module skeleton for **Accountant Workspace**. Intended boundary: separate dart mobile application with a flutter host for ios and android.

**Status: skeleton.** This repository supplies package/build structure and an explicit extension entry. It is not a completed feature, production API integration or registry publication. Existing implementations and package identities remain authoritative.

- Capability/source key: `liberusoftware/module-accounting-accountant-workspace`.
- Presentation scope: [Accountant Workspace](https://github.com/liberusoftware/documentation/blob/main/projects/accounting/features/accountant-workspace.md).
- Canonical ownership record: [source/plan group](https://github.com/liberusoftware/documentation/blob/main/projects/accounting/nextjs/accountant-workspace.md).
- Registry identity: `module_accounting_accountant_workspace_dart_mobile`.
- Foundation: [module-boilerplate-dart-mobile](https://github.com/liberusoftware/module-boilerplate-dart-mobile) at `0656c212b36ef4f8ffd6fc74db4ac541268e7d31`.

## Develop and verify

```bash
flutter pub get
flutter analyze
```

The public Dart entry exports `moduleDefinition`, a registration record. Add reviewed widgets, DTO mapping and injected services here. The package is not published to pub.dev, and it implements no native audio/device or business workflows yet.

Use the committed locks and declared toolchain. Read [AGENTS.md](AGENTS.md) and the [presentation runbook](https://github.com/liberusoftware/documentation/blob/main/guides/presentation/DART.md). Keep host routing, navigation, session integration and deployment outside reusable capability code. Keep Laravel policy, tenant context, validation, transactions, persistence and state transitions in the canonical owner. Do not infer endpoints or business DTOs from this registration descriptor.

Implement reviewed loading, empty, denied, invalid, stale/conflict, pending and recoverable failure states when adding real workflows. Test meaningful allowed/denied/wrong-tenant behavior against the authoritative API or public action. Reconcile uncertain writes before retrying and clear scoped cached data on logout. For device targets, review lifecycle, secure storage and platform support; a local draft is not a completed server transaction.

## Documented consumer project families

These project skeletons belong to documented consumer scopes. Their presence does not prove integration or feature parity; review compatible core/API contracts before enabling this package.

- [Accounting ERP](https://github.com/liberusoftware/project-accounting-erp-dart-mobile): Ledgers, tax, reporting and finance workflows.

## Other presentations of this capability

The companion repositories use the same canonical scope and preserve their own presentation lifecycle. Availability is recorded by the repository inventory; a repository link is not evidence of an implemented feature.

- [Laravel · Filament](https://github.com/liberusoftware/module-accounting-accountant-workspace-filament).
- [Laravel · Inertia · Vue](https://github.com/liberusoftware/module-accounting-accountant-workspace-vue-inertia).
- [Laravel · Inertia · React](https://github.com/liberusoftware/module-accounting-accountant-workspace-react-inertia).
- [Nuxt · Vue](https://github.com/liberusoftware/module-accounting-accountant-workspace-nuxt).
- [Next.js · React](https://github.com/liberusoftware/module-accounting-accountant-workspace-nextjs).
- [React Native · Expo](https://github.com/liberusoftware/module-accounting-accountant-workspace-react-native).
- [Flutter · Mobile](https://github.com/liberusoftware/module-accounting-accountant-workspace-flutter).
- [Dart · Desktop](https://github.com/liberusoftware/module-accounting-accountant-workspace-dart-desktop).

## Release boundary

Build and inspect a packed artifact in a clean consumer before an authorized registry release. Keep prerelease/skeleton status until implemented behavior and supported runtimes are verified. Repository creation does not publish to Packagist, npm or pub.dev. Native signing and store distribution are separate application responsibilities.
