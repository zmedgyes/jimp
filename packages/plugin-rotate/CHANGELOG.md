# v0.22.7 (Sat Feb 25 2023)

:tada: This release contains work from a new contributor! :tada:

Thank you, MD KHAIRUL ISLAM ([@black-turtle](https://github.com/black-turtle)), for all your work!

### Release Notes

#### use matrix rotate, if rotate angle is multiple of 90 degrees ([#1209](https://github.com/jimp-dev/jimp/pull/1209))

Fixes a bug where rotating by 90 degrees introduced extra pixels

---

#### 🐛 Bug Fix

- use matrix rotate, if rotate angle is multiple of 90 degrees [#1209](https://github.com/jimp-dev/jimp/pull/1209) ([@black-turtle](https://github.com/black-turtle))

#### Authors: 1

- MD KHAIRUL ISLAM ([@black-turtle](https://github.com/black-turtle))

---

# v0.22.1 (Mon Feb 06 2023)

#### 🏠 Internal

- rename master to main [#1169](https://github.com/jimp-dev/jimp/pull/1169) ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 1

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))

---

# v0.22.0 (Mon Feb 06 2023)

#### 🏠 Internal

- switch from should to expect [#1163](https://github.com/jimp-dev/jimp/pull/1163) ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Change test matching strategy to include all test files [#1161](https://github.com/jimp-dev/jimp/pull/1161) ([@danielholmes](https://github.com/danielholmes))

#### Authors: 2

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Daniel Holmes ([@danielholmes](https://github.com/danielholmes))

---

# v0.21.0 (Sun Feb 05 2023)

### Release Notes

#### Babel Refactor ([#1149](https://github.com/jimp-dev/jimp/pull/1149))

Marking this as a "breaking release" because it might change what deps need to be installed.

All modules should be exported as valid cjs and esm

![CleanShot 2023-02-04 at 18 19 27](https://user-images.githubusercontent.com/1192452/216798157-664cc430-7846-432d-84cf-26e8d8ba9e10.png)

---

#### 💥 Breaking Change

- Babel Refactor [#1149](https://github.com/jimp-dev/jimp/pull/1149) ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 1

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))

---

# v0.17.6 (Sat Feb 04 2023)

#### 🐛 Bug Fix

- fix documentation about rotation direction. [#1062](https://github.com/jimp-dev/jimp/pull/1062) ([@fabb](https://github.com/fabb))

#### Authors: 1

- [@fabb](https://github.com/fabb)

---

# v0.16.3 (Sat Feb 04 2023)

#### ⚠️ Pushed to `main`

- upgrade prettier ([@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 1

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))

---

# v0.11.0 (Fri May 15 2020)

#### 🚀 Enhancement

- Removed Core-JS as a dependency. [#882](https://github.com/oliver-moran/jimp/pull/882) ([@EricRabil](https://github.com/EricRabil))

#### Authors: 1

- Eric Rabil ([@EricRabil](https://github.com/EricRabil))

---

# v0.9.3 (Tue Nov 26 2019)

#### 🐛 Bug Fix

- `@jimp/cli`, `@jimp/core`, `@jimp/custom`, `jimp`, `@jimp/plugin-blit`, `@jimp/plugin-blur`, `@jimp/plugin-circle`, `@jimp/plugin-color`, `@jimp/plugin-contain`, `@jimp/plugin-cover`, `@jimp/plugin-crop`, `@jimp/plugin-displace`, `@jimp/plugin-dither`, `@jimp/plugin-fisheye`, `@jimp/plugin-flip`, `@jimp/plugin-gaussian`, `@jimp/plugin-invert`, `@jimp/plugin-mask`, `@jimp/plugin-normalize`, `@jimp/plugin-print`, `@jimp/plugin-resize`, `@jimp/plugin-rotate`, `@jimp/plugin-scale`, `@jimp/plugin-shadow`, `@jimp/plugin-threshold`, `@jimp/plugins`, `@jimp/test-utils`, `@jimp/bmp`, `@jimp/gif`, `@jimp/jpeg`, `@jimp/png`, `@jimp/tiff`, `@jimp/types`, `@jimp/utils`
  - Fix regeneratorRuntime errors [#815](https://github.com/oliver-moran/jimp/pull/815) ([@crutchcorn](https://github.com/crutchcorn) [@hipstersmoothie](https://github.com/hipstersmoothie))

#### Authors: 2

- Andrew Lisowski ([@hipstersmoothie](https://github.com/hipstersmoothie))
- Corbin Crutchley ([@crutchcorn](https://github.com/crutchcorn))
