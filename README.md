# TS Hybrid Boilerplate
Another boilerplate for ts projects, especifically to ts npm packages


## Description
A boiler plate that allow to generate TS hybrid packages with `mjs` and `cjs`

## Build package
Simply run `npm run build` and hybrid package will be generate
NOTE: Files under ./mjs will be reemplace lines with ".class" to ".class.js" to be compatible with browsers

## Release
At this moment package support `github` and `gitlab` CI/CD
Configure env vars to handle it.

- `NPM_TOKEN`: Allow to deploy to `npmjs.com` configure `.npmrc` to push package to another package repository
- `GH_TOKEN`: Allow to modify repository to add tags with releases (`GITHUB`)
- `GITLAB_TOKEN`: Allo to modify repository to add tags with releases (`GITLAB`)

Below it uses semantic-release so the semantic-release guide is: https://github.com/semantic-release/semantic-release

## NPM package to download and check compatibility

https://www.npmjs.com/package/ts-hybrid-boilerplate