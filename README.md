## aframe-environment-map-component

[![Version](http://img.shields.io/npm/v/aframe-environment-map-component.svg?style=flat-square)](https://npmjs.org/package/aframe-environment-map-component)
[![License](http://img.shields.io/npm/l/aframe-environment-map-component.svg?style=flat-square)](https://npmjs.org/package/aframe-environment-map-component)

Generate environment maps from aframe-environment-component for proper PBR reflections on metallic materials

Depends on [aframe-environment-component](https://github.com/feiss/aframe-environment-component) version >= 1.0.1

For [A-Frame](https://aframe.io).

<img src="/assets/before.jpg?raw=true" width=256 height=256/> Before

<img src="/assets/after.jpg?raw=true" width=256 height=256/> After

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
| position | Position of the CubeCamera to capture the environment.  Useful in case you need to get above an environments ground plane. | {x: 0, y: 1, z: 0}
| target | querySelector string representing any environment elements.  Anything matching this will be rendered in the environment map image | .environment (this is what is used in aframe-environment-component)        

### Installation

#### Browser

See the example

#### npm

Install via npm:

```bash
npm install aframe-environment-map-component
```

Then require and use.

```js
require('aframe');
require('aframe-environment-map-component');
```
