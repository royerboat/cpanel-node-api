# About the @cpanel/api Libraries
> This provides steps for using the cPanel API JavaScript and TypeScript libraries.

## Install
To install these libraries with Yarn, run:

```sh
$ yarn add @cpanel/api --registry http://127.0.0.1:4873
```

## Use
### TypeScript
```ts
import { api } from '@cpanel/api';

// TODO:
```

### JavaScript
```js
var api = require('api');

// TODO:

```

## Development
To develop using these:
1. Set up your development environment:
```sh
$ yarn install --dev
$ yarn run build
$ yarn run link:cpanel link:webmail link:whm
```
This lets you test the local version of your library rather than the one distributed on npm.dev.cpanel.net.
2. Make the changes to the library.
3. Rebuild the library:
```sh
$ yarn run build
```
4. Test your changes in one of the cPanel application spaces.

## Testing

To install the development dependencies, run:
```sh
$ yarn install --dev
$ yarn run test
```

## Publishing
When your changes are implemented and tested, and you're ready to publish, run:
```sh
$ yarn install
$ yarn run build
$ npm publish
```

## Contributing
Pull requests and stars are always welcome. For bugs and feature requests, [create a JIRA case](https://jira.cpanel.net)

## Authors

**Team Phoenix @ cPanel**

### Contributors
* Thomas Green <tomg@cpanel.net>
* Sruthi Sanigarapu <sruthi@cpanel.net>
* Aneece Yazdani <aneece@cpanel.net>

## License
Copyright © 2019 cPanel, L.L.C.
Licensed under the SEE LICENSE IN LICENSE license.
