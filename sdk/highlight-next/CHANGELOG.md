# @highlight-run/next

## 1.3.0

### Minor Changes

-   fix workspace:\* dependencies

### Patch Changes

-   Updated dependencies
    -   @highlight-run/node@1.3.0

## 2.0.0

### Major Changes

-   require project id for H.init
-   support for errors without associated sessions/requests

## 2.1.2

### Patch Changes

-   Adds support for Next.js `generateBuildId` config parameter, which will set Highlight `appVersion` if none is provided.

## 2.2.0

### Minor Changes

-   Adds ability to record `console` methods.

### 3.1.2

### Patch Changes

- Bumping to match `@highlight-run/node`

### 3.2.0

### Minor Changes

- Adding exports for `@highlight-run/next/client` and `@highlight-run/next/server`
    > We're hoping to remove `@highlight-run/next/highlight-init` and the default `@highlight-run/next` imports in favor of the new `/client` and `/server` varieties. For now we'll maintain the original imports as aliases.
- Adding `@highlight-run/node` and `highlight.run` to `peerDependencies`

### 4.0.0

### Major changes

- Removing exports for `@highlight-run/next` and `@highlight-run/next/highlight-init`. Import from `@highlight-run/next/server` and `@highlight-run/next/client` instead.
- Adding `excludedHostnames?: string[]` to `HighlightInit` props. Pass in a list of full or partial hostnames to prevent tracking: `excludedHostnames={['localhost', 'staging']}`.

### 4.1.0

### Minor changes

- Added support for setting metadata on `consumeError`

### 4.2.0

### Minor changes

- Added support for setting `serviceName`