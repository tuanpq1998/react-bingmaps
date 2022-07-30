# React-Bingmaps

Forked from [React-Bingmaps](https://github.com/iniamudhan/react-bingmaps)

## Added Features

- Multiple Polylines
- Handler event for polyline(s)

## Installation

### npm

```sh
$ npm i git+https://github.com/tuanpq1998/react-bingmaps.git
```

## Examples

```jsx
<ReactBingmaps
  bingmapKey="[YourBingMapsKey]"
  polyline={{
    location: [[13.0827, 80.2707],[13.0527, 80.2707]],
    option: { strokeColor: "red", strokeThickness: 10, strokeDashArray: [1, 2, 5, 10]},
    addHandler: {
      type : "click",
      callback : this.callbackFunc,
    }
  }}
  polylines={(
    [
      {
        location: [[13.0827, 80.2707],[13.0527, 80.2707]],
        option: { strokeColor: "red", strokeThickness: 10, strokeDashArray: [1, 2, 5, 10]},
        addHandler: {
          type : "mouseover",
          callback : this.callbackFunc,
        }
      },
    ],
    [
      {
        location: [[13.08, 80.27],[13.05, 80.26]],
        option: { strokeColor: "blue" },
        addHandler: {
          type : "click",
          callback : this.callbackFunc,
        }
      },
    ])}
></ReactBingmaps>
```

Detail: src/App.js
