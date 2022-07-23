# React-Bingmaps

Forked from [React-Bingmaps](https://github.com/iniamudhan/react-bingmaps)

## Added Features

- Multiple Polyline

## Installation

### npm

```sh
$ npm i git+https://github.com/tuanpq1998/react-bingmaps.git
```

## Examples

```jsx
<ReactBingmaps
  bingmapKey = "[YourBingMapsKey]"
  ...
  polylines = {
  	[{
      "location": [[13.0827, 80.2707],[13.0527, 80.2707]],
      "option": { strokeColor: 'red', strokeThickness: 10, strokeDashArray: [1, 2, 5, 10] }
    }], [{
      "location": [[13.0800, 80.2700],[13.0500, 80.2600]],
      "option": { strokeColor: 'blue' }
    }]}>
</ReactBingmaps>
```

Detail: src/App.js
