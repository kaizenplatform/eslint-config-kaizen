# eslint-config-kaizen

ESLint shareable config for Kaizen Platform

## Installation

1. This config is based on `eslint-config-airbnb`. Run this command to install `eslint-config-airbnb` and its dependencies.

  ```sh
  (
    export PKG=eslint-config-airbnb;
    npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs npm install --save-dev "$PKG@latest"
  )
  ```

2. Then, install `eslint-config-kaizen`.

  ```sh
  $ npm install --save-dev kaizenplatform/eslint-config-kaizen
  ```

## Usage

Add the ESLint config to your `.eslintrc`:

```json
{
  "extends": "kaizen"
}
```
