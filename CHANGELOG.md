# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [4.0.5](https://github.com/awran5/react-simple-star-rating/compare/v4.0.4...v4.0.5) (2021-12-13)

### [4.0.4](https://github.com/awran5/react-simple-star-rating/compare/v4.0.3...v4.0.4) (2021-12-13)


### Bug Fixes

* handle  value issue [#7](https://github.com/awran5/react-simple-star-rating/issues/7) ([b28b534](https://github.com/awran5/react-simple-star-rating/commit/b28b534ce6a55bf18ff38817f1bd59610769eb4b))

### [4.0.3](https://github.com/awran5/react-simple-star-rating/compare/v4.0.2...v4.0.3) (2021-12-11)


### Bug Fixes

* click on touch devices ([cee11c2](https://github.com/awran5/react-simple-star-rating/commit/cee11c2e7fa2e23d872395fbaa1dc9f527aa4591))

### [4.0.2](https://github.com/awran5/react-simple-star-rating/compare/v4.0.0...v4.0.2) (2021-12-10)


### Bug Fixes

* fix [#6](https://github.com/awran5/react-simple-star-rating/issues/6) not working on mobile browsers ([d0c1c4d](https://github.com/awran5/react-simple-star-rating/commit/d0c1c4d31fa2209215ccbc3b1dfb386d0a46e49a))
* **responsive issue:** add missing CSS to fix responsive ([5e20f1e](https://github.com/awran5/react-simple-star-rating/commit/5e20f1e78ea1480620b9ffc0303a3f646dfe3bcf))

## 2.0.0

### Major Changes

- Removed: CSS stylesheet.
- Removed: Label Prop
- Update: Package dependencies.
- Added: Eslint airbnb style.
- Added: RatingView Component
- Added: Ability to add a custom SVG icon

# 4.0.0

- rename: `star` prop to `iconsCount`
- remove: `width`, `height` you can use `size` prop instead
- add: `readonly` prop
- add: `fillColorArray` prop to add a color range
- add: `fullIcon`, `emptyIcon`, `customIcons` for add a custom SVG icons
- add: `rtl` for RTL support
- add: `allowHalfIcon` prop to enable a fractional icon (half icon)
- add: `allowHover` enable / disable hover effect
- add: `showTooltip` prop to show a tooltip with live values with other `props` to customize
