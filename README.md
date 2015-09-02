# csv3geojson

Faster CSV to GeoJSON that only supports node.js and streams.

It's less user-friendly, not available as a library, not compatible with
browsers, but also a lot faster.

```
~/src/csv3geojson〉time ./csv3geojson LON LAT < ~/Downloads/us/va/statewide.csv > statewide.geojson
./csv3geojson LON LAT < ~/Downloads/us/va/statewide.csv > statewide.geojson  63.35s user 9.62s system 95% cpu 1:16.32 total
```
