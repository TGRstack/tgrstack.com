---
layout: default
---

# TGRStack (Typescript GraphQL React)
[![TypeScript](https://img.shields.io/badge/TypeScript-2.8.3-blue.svg?style=flat-square)](https://github.com/Microsoft/TypeScript)
[![styled with TSLint](https://img.shields.io/badge/styled_with-TSLint-ff69b4.svg?style=flat-square)](https://github.com/palantir/tslint/)
[![WebPack](https://img.shields.io/badge/WebPack-4.5.0-blue.svg?style=flat-square)](https://github.com/Microsoft/TypeScript)
[![Node](https://img.shields.io/badge/Node-8.11.2-blue.svg?style=flat-square)](https://github.com/Microsoft/TypeScript)

[![NPS friendly](https://img.shields.io/badge/NPS-friendly-brightgreen.svg?style=flat-square)](https://github.com/kentcdodds/nps)
[![Commitizen friendly](https://img.shields.io/badge/Commitizen-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)
[![Semver friendly](https://img.shields.io/badge/SemVer-friendly-brightgreen.svg?style=flat-square)](http://commitizen.github.io/cz-cli/)

This site is the collection point for 4 projects [Falieson](https://www.github.com/falieson) has released or is in the process of releasing.

These projects are all starter-kits that use a common set of utilities and patterns that are designed for a pleasant and productive scalable developer experience. The core technologies for these projects are 2018's "state of the art" for javascript; these are: **_TypesScript_**, **_GraphQL_**, and **_React_**. Combined these libraries form the cornerstone for a full-stack web development experience that is hardened against bugs and trains developers of all experience-levels to write efficient code.

{% if site.feedback_url %}
  <a href="{{ site.feedback_url }}" class="btn">Send TGR Feedback</a>
{% endif %}

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

## Comparison and Progress
[Spreadsheet Comparison](https://docs.google.com/spreadsheets/d/1bwTX1OGK3sYrHuOE60HCpxQbccWZ8gmDVpYG2AvacrA/edit?usp=sharing) - Pick a Topic to comment on or select an empty row to add a topic

With this list you can see how far I've gotten in my development directories. **Expect the github repos to be a little bit behind this spreadsheet; especially at first as I ramp up on publishing writeups about each major stage.**
~ Falieson 2018-05-30

## Timeline

I am releasing the code incrementally throughout June 2018. Each major branch comes with a tutorial explaining the major advancements so you can understand how these were built.

(year-week) \<goal>
- 2018-22: 
- 

# Typescript-Module
{% include downloads.html repo_url='https://github.com/Falieson/2018-typescript-module' %}

## Articles

- 2018-05-31: **TS Module: Part 1.** Best Practices w/ Declarations
- 2018-06-01: **TS Module: Part 2.** JS Utilities for a great Developer Experience
- 2018-06-05: **TS Module: Part 3.** Testing
- 2018-06-06: **TS Module: Part 4.** Linting
- 2018-06-07: **TS Module w/ Webpack: Part 1.** Setting up Webpack

# Typescript-React-Module
{% include downloads.html coming_soon=true repo_url='https://github.com/Falieson/2018-typescript-react-module' %}

<!-- ## Typescript-React-Native-Module -->
# Typescript-GraphQL-Endpoint
{% include downloads.html coming_soon=true repo_url='https://github.com/Falieson/2018-typescript-graphql-endpoint' %}

# Typescript-GraphQL-React-Fullstack
{% include downloads.html coming_soon=true repo_url='https://github.com/Falieson/2018-typescript--graphql-react-fullstack' %}

# TBD...

1. Guiding Principles
2. Common Packages

# Links
Find Falieson (aka Florian Mettetal) on...
 {% include social.html %}

{% if site.feedback_url %}
  <a href="{{ site.feedback_url }}" class="btn">Send TGR Feedback</a>
{% endif %}
