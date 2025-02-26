# @milkdown/exception

## 7.2.0

### Minor Changes

- f5e00085: Add inspector and telemetry.

### Patch Changes

- 45cd3c76: Fix circular deps in commands plugin.
- c69f3076: Rename inspection to telemetry
- 10139088: Fix incorrect system plugin store ref.
- 828cceb9: Add support for editor inspector #960

## 7.1.2-next.3

### Patch Changes

- 10139088: Fix incorrect system plugin store ref.

## 7.1.2-next.2

### Patch Changes

- c69f3076: Rename inspection to telemetry

## 7.1.2-next.1

### Patch Changes

- 45cd3c76: Fix circular deps in commands plugin.

## 7.1.2-next.0

### Patch Changes

- 828cceb9: Add support for editor inspector #960

## 7.1.1

### Patch Changes

- f4aaf467: Use slugify to create id for heading nodes
  Fix inline sync plugin causes unneeded changes #924
  Upgrade typescript version to 5 #943
  Add hard break leafText #944

## 7.1.0

### Minor Changes

- 4a60eae7: Add support for HTML nodes.
  Export css files from prosemirror packages.

## 7.0.1

### Patch Changes

- 52dcbbe8: Bug fix.

## 7.0.0

### Major Changes

- 069d719b: Milkdown v7.

  - The editor becomes a first-class headless component.
  - Factory plugins are deprecated and replaced by composable plugins.
  - Runtime plugin toggle.
  - Universal widget plugins.
  - Better Vue and React support.
  - API documentation.

### Patch Changes

- 46010daf: Fix bugs of async composables.
- 2ad4b566: Fix some bugs for rc version.
- ff8a568b: Fix issues in nord-theme and block-plugin.
- 76bed778: Align the API of block plugin with slash and tooltip.
- fc2f4f94: Bug fix version
- cbe8b734: Upgrade prosemirror version and rename collab plugin

## 7.0.0-next.6

### Patch Changes

- cbe8b734: Upgrade prosemirror version and rename collab plugin

## 7.0.0-next.5

### Patch Changes

- 76bed778: Align the API of block plugin with slash and tooltip.

## 7.0.0-next.4

### Patch Changes

- 46010daf: Fix bugs of async composables.

## 7.0.0-next.3

### Patch Changes

- ff8a568b: Fix issues in nord-theme and block-plugin.

## 7.0.0-next.2

### Patch Changes

- fc2f4f94: Bug fix version

## 7.0.0-next.1

### Patch Changes

- 2ad4b566: Fix some bugs for rc version.

## 7.0.0-next.0

### Major Changes

- 069d719b: Pre-release for milkdown v7.

## 6.5.4

### Patch Changes

- b4003d9: Fix bugs and make some small improvements.

## 6.5.3

### Patch Changes

- d5c337d: Ux improvements and bug fix.

## 6.5.2

### Patch Changes

- 3cb8683: Fix floating widget positions by @iHaPBoy

## 6.5.0

### Minor Changes

- 77ae1d3: Removable plugins, editor status, table inputrule and `injectSlices` factory options.

## 6.4.1

### Patch Changes

- c1fd2fe2: Bug fix for android list and prism SSR.

## 6.4.0

### Minor Changes

- cd6a6139: Inline sync plugin, vscode paste support, and new internal ctx.

## 6.3.2

### Patch Changes

- 161d7104: Fix bug of plugin-menu, react strict mode and muptiple editors.

## 6.3.1

### Patch Changes

- 8478db7a: Fix bug for memory leak, hardbreak and em to px.

## 6.3.0

### Minor Changes

- d3b2bd9d: https://github.com/Saul-Mirone/milkdown/milestone/4

## 6.2.0

### Minor Changes

- 26afcdaf: New react and vue API, custom heading id, prosemirror upgrade, and async composable API.

## 6.1.5

### Patch Changes

- ccf70357: Fix extended factories cannot inject slices

## 6.1.4

### Patch Changes

- d866dded: Fix bugs for clipboard plugin and i18 support

## 6.1.3

### Patch Changes

- b5bb4c3f: Fix bugs: inline nodes cursor, theme & emoji for next/nuxt, hardbreak only paragraph.

## 6.1.2

### Patch Changes

- 2c651a96: Fix bugs for collab editing and theme.

## 6.1.1

### Patch Changes

- 1b52931a: Fix input chip bug

## 6.1.0

### Minor Changes

- 1daf87dd: Improve support for collaborative editing.

## 6.0.2

### Patch Changes

- e956c5e3: Fix bugs for collaboration mode

## 6.0.1

### Patch Changes

- 08a442de: Fix peer dependency error

## 6.0.0

### Major Changes

- 00dcdee9: Release milkdown@6
- 4c2846d5: Release milkdown@v6 next.

### Patch Changes

- e27e7e62: Improve UX and API.

## 6.0.0-next.1

### Patch Changes

- e27e7e62: Improve UX and API.

## 6.0.0-next.0

### Major Changes

- 4c2846d5: Release milkdown@v6 next.

## 5.5.0

### Minor Changes

- d79264e6: Prism plugin now can be configured. And bug fixes with UX optimization.

## 5.4.1

### Patch Changes

- 1a882652: Quick fix for new dep orgnization

## 5.4.0

### Minor Changes

- 6eef6cd1: Bug fixes, UX improvements and dependency optimization.

## 5.3.5

### Patch Changes

- d28d71c1: Bug fixes and ux improvements

## 5.3.4

### Patch Changes

- 1e8cce33: Image load status improvement and support for heading id

## 5.3.3

### Patch Changes

- f7609d48: Bug fix and ux improvements

## 5.3.2

### Patch Changes

- d62a6011: Bug fixes and new listener API

## 5.3.1

### Patch Changes

- 0f32decd: Bug fixe and ux improvement

## 5.3.0

### Minor Changes

- ed679a03: Optimize vue and react renderer.

## 5.2.1

### Patch Changes

- eb74e3b5: Add es and cjs bundle, fix bugs and improve ux

## 5.2.0

### Minor Changes

- 42055660: Add menu plugin and lots of optimize.

## 5.1.2

### Patch Changes

- b25da66e: Fix add mark issue for hr

## 5.1.1

### Patch Changes

- e7c701a1: Fix view configuration.

## 5.1.0

### Minor Changes

- 9519c4c4: Add composable plugins API.

## 5.0.1

### Patch Changes

- 1538bd4a: Fix bugs

## 5.0.0

### Major Changes

- 35e76858: Refactor the plugin system

## 4.14.2

### Patch Changes

- 29861bee: Upgrade remark version

## 4.14.1

### Patch Changes

- b2618f24: Rollback heading slug feature.

## 4.14.0

### Minor Changes

- e942946d: Add prose and ctx package, improve UX and fix bugs.

## 4.13.3

### Patch Changes

- db2e3e59: Add indent plugin and upload plugin

## 4.13.2

### Patch Changes

- 5d6ec991: Fix image command bug

## 4.13.1

### Patch Changes

- bd5925e3: Fix sourcemap missing files issue

## 4.13.0

### Minor Changes

- 2d339e90: UX and binding optimize

## 4.12.0

### Minor Changes

- 4207ca0e: Support diagram plugin.

## 4.11.2

### Patch Changes

- dfe441db: Add config for slash, tooltip and image

## 4.11.1

### Patch Changes

- fca77942: Export theme module

## 4.11.0

### Minor Changes

- 80a0c815: Add slots in design system and headless mode for all plugins.

## 4.10.5

### Patch Changes

- 8e2d440: rgba color fix

## 4.10.4

### Patch Changes

- 3b5bbdf: Add rgb and rgba support for theme

## 4.10.3

### Patch Changes

- 3903547: Add HTML filter plugin

## 4.10.2

### Patch Changes

- 447044b: Fix list issue in gfm

## 4.10.1

### Patch Changes

- 61d847d: Add side effect marker

## 4.10.0

### Minor Changes

- 5868165: Add design system for write theme easily.

## 4.9.6

### Patch Changes

- f4a9bb1: Fix circular deps for preset-gfm

## 4.9.5

### Patch Changes

- 22d5c36: UI optimize and bug fix.

## 4.9.4

### Patch Changes

- abd6ed9: Add license and fix bugs.

## 4.9.3

### Patch Changes

- 566d83f: Release to github release packages.

## 4.9.2

### Patch Changes

- 7c84b8e: Release for github

## 4.9.1

### Patch Changes

- 59065b6: Fix ci issues

## 4.9.0

### Minor Changes

- cbce961: Add command manager.

## 4.8.2

### Patch Changes

- 83ad3c9: Make performance and ux improvements.

## 4.8.1

### Patch Changes

- 6d801db: Refactor for small improvements.

## 4.8.0

### Minor Changes

- 501ad84: Add emoji plugin

## 4.7.1

### Patch Changes

- 7ab83ca: Fix dep list.

## 4.7.0

### Minor Changes

- 804cbb5: Add support for clipboard and collaborative abilities.
