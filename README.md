# example-github-action

[![Build](https://github.com/relative-ci/example-github-action/actions/workflows/build.yaml/badge.svg)](https://github.com/relative-ci/example-github-action/actions/workflows/build.yaml)
[![RelativeCI](https://badges.relative-ci.com/badges/WlBer9l4ubfYdd628kB6?branch=master)](https://app.relative-ci.com/projects/WlBer9l4ubfYdd628kB6)

> [@relative-ci/agent](https://github.com/relative-ci/agent) [Github Action](https://github.com/features/actions) example


## Example app

Basic webpack setup:
- `Javascript`: babel with `@babel/preset-env` and `@babel/preset-react`
- `CSS`: `postcss`(`autoprefixer`, `cssnano`), `css-modules`, `mini-css-extract`
- assets:
  - `public`: `copy-webpack-plugin`
  - `src`: `file-loader`
  - `inline.svg`: - `svgr`
