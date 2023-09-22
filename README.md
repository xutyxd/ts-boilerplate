# TS Hybrid Boilerplate
Another boilerplate for ts projects, especifically to ts npm packages


## Description
A boiler plate that allow to generate TS hybrid packages with `mjs` and `cjs`

## Build package
Simply run `npm run build` and hybrid package will be generate

## Release
At this moment package support `github` and `gitlab` CI/CD
Configure env vars to handle it.

- `NPM_TOKEN`: Allow to deploy to `npmjs.com` configure `.npmrc` to push package to another package repository
- `GH_TOKEN`: Allow to modify repository to add tags with releases (`GITHUB`)
- `GITLAB_TOKEN`: Allo to modify repository to add tags with releases (`GITLAB`)


## NPM Package to download and check it compatibility

https://www.npmjs.com/package/ts-hybrid-boilerplate