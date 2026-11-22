# @collana-solutions/reactstrap

## 10.0.1

### Patch Changes

- [#16](https://github.com/collana-solutions/reactstrap/pull/16) [`0a166c9`](https://github.com/collana-solutions/reactstrap/commit/0a166c95deb30cb8ab378663cf5b349b455c2ca2) Thanks [@neotrow](https://github.com/neotrow)! - The package is now published as `@collana-solutions/reactstrap`. The components and the API are unchanged, and 10.0.0 is available under the new name as well. To migrate, replace the old package with the new one:

  ```shell
  npm uninstall @neolution-ch/reactstrap
  npm install @collana-solutions/reactstrap
  ```

  Then change the imports:

  ```js
  import { Button } from '@collana-solutions/reactstrap';
  ```

  `@neolution-ch/reactstrap` gets deprecated and receives no further releases.

## [10.0.0] - 2026-02-24

- Added support for React 19

[10.0.0]: https://github.com/neolution-ch/reactstrap/compare/10.0.0-rc.0...10.0.0
