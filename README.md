# react-collapse

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/nkbt/help)

[![Circle CI](https://circleci.com/gh/nkbt/react-collapse.svg?style=svg)](https://circleci.com/gh/nkbt/react-collapse)
[![Coverage Status](https://coveralls.io/repos/nkbt/react-collapse/badge.svg?branch=master)](https://coveralls.io/r/nkbt/react-collapse?branch=master)
[![Dependency Status](https://david-dm.org/nkbt/react-collapse.svg)](https://david-dm.org/nkbt/react-collapse)
[![devDependency Status](https://david-dm.org/nkbt/react-collapse/dev-status.svg)](https://david-dm.org/nkbt/react-collapse#info=devDependencies)

Component-wrapper for collapse animation with react-motion for elements with variable (and dynamic) height


![React Collapse](src/example/react-collapse.gif)


## Installation

### npm

```sh
npm install --save react-collapse
```

### bower

```js
// TODO
```

## Demo

[http://nkbt.github.io/react-collapse/example](http://nkbt.github.io/react-collapse/example)

## Codepen demo

```js
// TODO
```

## Usage

```js
<Collapse isOpened={true || false}>
  <div>Random content</div>
</Collapse>
```


## Options


#### `isOpened`: PropTypes.boolean.isRequired

Expands or collapses content


#### `children`: PropTypes.node.isRequired

One or multiple children with static, variable or dynamic height


#### Pass-through props

All other props are applied to a container that is being resized. So it is possible to pass `style` or `className`, for example.


## Development and testing

To run example covering all `ReactCollapse` features, use `npm start`, which will compile `src/example/Example.js`

```bash
git clone git@github.com:nkbt/react-collapse.git
cd react-collapse
npm install
npm start

# then
open http://localhost:8080
```

## License

MIT
