---
'@collana-solutions/reactstrap': patch
---

The package is now published as `@collana-solutions/reactstrap`. The components and the API are unchanged, and 10.0.0 is available under the new name as well. To migrate, replace the old package with the new one:

```shell
npm uninstall @neolution-ch/reactstrap
npm install @collana-solutions/reactstrap
```

Then change the imports:

```js
import { Button } from '@collana-solutions/reactstrap';
```

`@neolution-ch/reactstrap` gets deprecated and receives no further releases.
