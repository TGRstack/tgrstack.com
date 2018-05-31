# tgrstack.com
[![TypeScript](https://img.shields.io/badge/TypeScript-2.8.3-blue.svg?style=flat-square)](https://github.com/Microsoft/TypeScript)
[![styled with TSLint](https://img.shields.io/badge/styled_with-TSLint-ff69b4.svg?style=flat-square)](https://github.com/palantir/tslint/)
[![WebPack](https://img.shields.io/badge/WebPack-4.5.0-blue.svg?style=flat-square)](https://github.com/Microsoft/TypeScript)
[![Node](https://img.shields.io/badge/Node-8.11.2-blue.svg?style=flat-square)](https://github.com/Microsoft/TypeScript)

[![NPS friendly](https://img.shields.io/badge/NPS-friendly-brightgreen.svg?style=flat-square)](https://github.com/kentcdodds/nps)
[![Commitizen friendly](https://img.shields.io/badge/Commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)
[![Semver friendly](https://img.shields.io/badge/SemVer-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)


## More info and articles at TGRStack.com
[TGRStack.com](http://tgrstack.com/) - Documentation, Articles

## Repositories
- [2018-typescript-module](https://github.com/Falieson/2018-typescript-module)
- [2018-typescript-react-module](https://github.com/Falieson/2018-typescript-react-module) - Coming Soon
- [2018-typescript-graphql-endpoint](https://github.com/Falieson/2018-typescript-graphql-endpoint) - Coming Soon
- [2018-typescript-graphql-react-fullstack](https://github.com/Falieson/2018-typescript-graphql-react-fullstack) - Coming Soon

## Features

### Core

- :rocket: ES2018+ support syntax that is stage-3 or later in the TC39 process.
- :fire:  Hot development restarts dev-server when your src changes
- :control_knobs:  Preconfigured to support development and optimized production builds
- :notes:  `typescript` incremental returns reducing development bugs
- :vertical_traffic_light:  `tslint` configured for strict, consistent, code style

### Tests

- :performing_arts: `jest` as the test framework.
- :performing_arts: `ts-jest` configured to test TS files, uses tsconfig.jest.json, and skip babel.

### Build (w/ Webpack)

- :package:  All source is bundled using Webpack v4
- :star2:  webpack merge, splitting config for dev, prod, common
- :vertical_traffic_light:   ts-loader for compiling typescript
- :sweat_drops:  babel-loader for additional polyfills (browser support)
- :sunglasses:  HappyPack for multi-core building
- :robot:  Auto generated Vendor DLL for smooth development experiences
- :leaves:  Tree-shaking

### Utils

- :video_game:  `nps` node-package-scripts removes the limitation of package.json enabling JS & //comments .  Modify `/package-scripts.js` and use `nps <command>` instead of `npm run <command>`.
- :raised_hands:  `commitizen` to help us generate beautifully formatted and consistent commit messages.
- :joy_cat:  `cz-emoji` is a plugin for commitizen that adds emoji to the commit template.
- :trophy:  `standard-version` is a replacement for `npm version` with automatic CHANGELOG generation
- :white_check_mark:  `validate-commit-msg` validates commit messages to follow commitizen patterns
