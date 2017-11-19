<h1 align="center">
  <a href="https://github.com/simonepri/geo-maps"><img src="https://raw.githubusercontent.com/simonepri/geo-maps/master/media/geo-maps.jpg" alt="geo-maps" /></a>
</h1>
<div align="center">
  <a href="https://github.com/tmcw/awesome-geojson"><img src="https://awesome.re/mentioned-badge.svg" alt="awesome-geojson" /></a>
  <a href="http://geojson.org/"><img src="https://img.shields.io/badge/resolution-{{resolution}}-f1c40f.svg" alt="map resolution" /></a>
  <a href="https://github.com/simonepri/geo-maps"><img src="https://badges.herokuapp.com/size/npm/@geo-maps/countries-coastline-{{resolution}}/world.geo.json" alt="map size" /></a>
  <a href="https://www.npmjs.com/package/@geo-maps/countries-coastline-{{resolution}}"><img src="https://img.shields.io/npm/dm/@geo-maps/countries-coastline-{{resolution}}.svg" alt="npm downloads" /></a>
  <a href="https://www.npmjs.com/package/@geo-maps/countries-coastline-{{resolution}}"><img src="https://img.shields.io/npm/v/@geo-maps/countries-coastline-{{resolution}}.svg" alt="npm version" /></a>
  <a href="http://geojson.org/"><img src="https://img.shields.io/badge/format-GeoJSON-e67e22.svg" alt="maps format" /></a>
  <a href="http://www.openstreetmap.org/"><img src="https://img.shields.io/badge/source-OSM-2ecc71.svg" alt="map source" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/simonepri/geo-maps.svg" alt="software license" /></a>
  <a href="https://opendatacommons.org/licenses/odbl/1.0/"><img src="https://img.shields.io/badge/license-ODbL-2980b9.svg" alt="data license" /></a>
</div>
<br />
<div align="center">
  🗺 High Quality GeoJSON map of countries' political coastline boundaries with {{resolution}} resolution.
</div>
<div align="center">
  <sub>
    The only GeoJSON maps of the world you will ever need!
  </sub>
</div>

## Preview
Click on the image below to see a live preview of the map with an absolute error
of **{{resolution}}**.  

<p align="center">
  <a alt="World Boundaries" href="http://mapshaper.org/?files=https://unpkg.com/@geo-maps/countries-coastline-{{resolution}}/map.geo.json">
    <img src="https://raw.githubusercontent.com/simonepri/geo-maps/rework/media/geo-maps-countries-coastline-shape.png" width ="49%"/>
  </a>
  <a alt="World Boundaries" href="http://geojson.io/#data=data:text/x-url,https://unpkg.com/@geo-maps/countries-coastline-{{resolution}}/map.geo.json">
    <img src="https://raw.githubusercontent.com/simonepri/geo-maps/rework/media/geo-maps-countries-coastline-hover.png" width ="49%"/>
  </a>
</center>

## Install
```bash
$ npm install --save @geo-maps/countries-coastline-{{resolution}}
```

## Usage
```javascript
// Just require it and you are done!
const geoCountriesCoastline = require('@geo-maps/countries-coastline-{{resolution}}');
```

## Authors
* **Simone Primarosa** - [simonepri](https://github.com/simonepri)

See also the list of [contributors](https://github.com/simonepri/geo-maps/contributors) who participated in this project.

## License
All data of this project is licensed under the [Open Data Commons Public Domain Dedication and License](https://opendatacommons.org/licenses/odbl/1.0/) as stated in [OpenStreetMap License](http://www.openstreetmap.org/copyright)

All source code of this project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
