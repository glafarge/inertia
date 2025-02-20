# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For changes prior to v1.0.0, see the [legacy releases](https://legacy.inertiajs.com/releases).

## [Unreleased](https://github.com/inertiajs/inertia/compare/v1.0.0...HEAD)

- Nothing!

## [v1.0.0](https://github.com/inertiajs/inertia/compare/7ce91ec...v1.0.0) - 2023-01-14

### Added

- Added SSR support to Svelte library ([#1349](https://github.com/inertiajs/inertia/pull/1349))
- Added first-class TypeScript support to React adapter
- Added first-class TypeScript support to Vue 2 adapter
- Added first-class TypeScript support to Vue 3 adapter
- Added new `useForm()` hook to Vue 2 adapter ([ff59196](https://github.com/inertiajs/inertia/commit/ff59196))

### Changed

- Renamed `@inertiajs/inertia` library to `@inertiajs/core` ([#1282](https://github.com/inertiajs/inertia/pull/1282))
- Renamed `@inertiajs/inertia-react` library to `@inertiajs/react` ([#1282](https://github.com/inertiajs/inertia/pull/1282))
- Renamed `@inertiajs/inertia-svelte` library to `@inertiajs/svelte` ([#1282](https://github.com/inertiajs/inertia/pull/1282))
- Renamed `@inertiajs/inertia-vue` library to `@inertiajs/vue2` ([#1282](https://github.com/inertiajs/inertia/pull/1282))
- Renamed `@inertiajs/inertia-vue3` library to `@inertiajs/vue3` ([#1282](https://github.com/inertiajs/inertia/pull/1282))
- Merged progress library to core and deprecated `@inertiajs/progress` library ([#1282](https://github.com/inertiajs/inertia/pull/1282), [0b5f773](https://github.com/inertiajs/inertia/commit/0b5f773))
- Merged server library to core and deprecated `@inertiajs/server` library ([#1282](https://github.com/inertiajs/inertia/pull/1282))
- Renamed `Inertia` named export to `router` ([#1282](https://github.com/inertiajs/inertia/pull/1282), [e556703](https://github.com/inertiajs/inertia/commit/e556703))
- Removed deprecated named exports ([#1282](https://github.com/inertiajs/inertia/pull/1282), [e556703](https://github.com/inertiajs/inertia/commit/e556703))
- Removed deprecated `app` argument from `createInertiaApp()` in Vue adapters ([#1282](https://github.com/inertiajs/inertia/pull/1282), [65f8a5f](https://github.com/inertiajs/inertia/commit/65f8a5f))
- Updated axios to 1.x ([#1377](https://github.com/inertiajs/inertia/pull/1377))
- Simplified `usePage()` hook in Vue 3 adapter ([#1373](https://github.com/inertiajs/inertia/pull/1373))
- Improved Svelte `use:inertia` and `<Link />` component ([#1344](https://github.com/inertiajs/inertia/pull/1344))
- Removed global `visitOptions()` hook ([#1282](https://github.com/inertiajs/inertia/pull/1282), [30908c2](https://github.com/inertiajs/inertia/commit/30908c2))
- Switched bundler from Microbundle to ESbuild ([f711b46](https://github.com/inertiajs/inertia/commit/f711b46), [8093713](https://github.com/inertiajs/inertia/commit/8093713), [342312d](https://github.com/inertiajs/inertia/commit/342312d), [c9e12b3](https://github.com/inertiajs/inertia/commit/c9e12b3))

### Fixed

- Fixed `<title>` tag not always being included when a `title` callback is defined in `createInertiaApp()` ([#1055](https://github.com/inertiajs/inertia/pull/1055))
- Fixed types to include `undefined` as a valid `FormDataConvertable` option ([#1165](https://github.com/inertiajs/inertia/pull/1165))
- Fixed issue where remembered state wasn't clear on a full page reload ([769f643](https://github.com/inertiajs/inertia/commit/769f643))
