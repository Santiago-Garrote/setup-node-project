# setup-frontend

<!--toc:start-->
- [setup-frontend](#setup-frontend)
  - [Features](#features)
  - [Inputs](#inputs)
  - [Usage](#usage)
<!--toc:end-->

Reusable GitHub Action to setup frontend projects.

## Features
- Node.js setup
- pnpm optional support
- Dependency caching
- Lockfile-aware install
- Works with pnpm, npm, yarn

## Inputs

| Name | Default | Description |
|----|----|----|
| node-version | 20 | Node.js version |
| pnpm-version | 10 | pnpm version (empty disables pnpm) |
| working-directory | . | Project directory |

## Usage

```yaml
- uses: santiago-garrote/setup-frontend@vX
  with:
    node-version: 20
    pnpm-version: 10
    working-directory: frontend

