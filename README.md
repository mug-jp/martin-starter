# martin-starter

## usage

This starter is built to run with Docker compose v2.

```sh
cd martin-starter
docker compose up -d
```

Then, you can access the app at http://localhost:3000

- catalog: `http://localhost:3000/catalog`
- sprite: `http://localhost:3000/sprite/maki[.png|.json]`

## data

- /martin/maki: https://github.com/mapbox/maki
- /martin/tile/points.mbtiles: https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P29-v2_0.html
- /martin/tile/polygons.pmtiles: https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v3_1.html