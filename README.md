# agba-logger

## Installation

``` bash
$ npm install agba-logger --save
```
or 

``` bash
$ pnpm add -D agba-logger
```
or 

``` bash
$ yarn add -d agba-logger
```

## Usage

``` js
// v3.x.x
const log = require('agba-logger')({
  debug: false,
  silent: false
});
log.info('Hello world');

// v4.x.x
const log = require('agba-logger').default({
  debug: false,
  silent: false
});
log.info('Hello world');

// v4.x.x (ES Module)
import { logger } from 'agba-logger';

const log = logger({
  debug: false,
  silent: false
});
log.info('Hello world');
```

Option | Description | Default
--- | --- | ---
`debug` | Display debug message. | `false`
`silent` | Don't display any message in console. | `false`

## License

MIT