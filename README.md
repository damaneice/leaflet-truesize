# Leaflet Truesize

Plugin for creating projection aware draggable polygons and polylines.
You can find the docs on the plugin [website](https://wbkd.github.io/leaflet-truesize/).


## Installation

You need [Leaflet](http://leafletjs.com/) in order to run this plugin.

Install with npm/yarn:
```shell
$ npm install leaflet-truesize
```

Or download the minified library from [unpkg](https://unpkg.com/leaflet-truesize/build/Leaflet.TrueSize.min.js) or [jsDelivr](https://cdn.jsdelivr.net/npm/leaflet-truesize).
```html
<script src="https://unpkg.com/leaflet-truesize"></script>
```

## Usage

```javascript
import L from 'leaflet';
import 'leaflet-truesize';

// create leaflet map ...

const trueSizeLayer = new L.trueSize(geojsonFeature, {
  color: '#FF0000',
  weight: 1,
  opacity: 1,
  dashArray: '7, 10',
}).addTo(map);
```
