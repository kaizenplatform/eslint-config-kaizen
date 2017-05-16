# eslint-config-kaizen

ESLint shareable config for Kaizen Platform

## Installation

1. This config is based on [`eslint-config-airbnb`](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb). Install `eslint-config-airbnb` and its dependencies first by the following command:
  
  With npm:

  ```sh
  (
    export PKG=eslint-config-airbnb;
    npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs npm install --save-dev "$PKG@latest"
  )
  ```
  
  With yarn:
  ```sh
  (
    export PKG=eslint-config-airbnb;
    npm info "$PKG@latest" peerDependencies --json | command sed 's/[\{\},]//g ; s/: /@/g' | xargs yarn add --dev "$PKG@latest"
  )
  ```



2. Then, install `eslint-config-kaizen`

  ```sh
  # npm
  $ npm install --save-dev kaizenplatform/eslint-config-kaizen
  
  # yarn
  $ yarn add --dev kaizenplatform/eslint-config-kaizen
  ```

## Usage

Add `"extends": "kaizen"` to your `.eslintrc`

```json
{
  "extends": "kaizen"
}
```

## License

Code released under [the MIT license](https://github.com/kaizenplatform/eslint-config-kaizen/blob/master/LICENSE.md).
