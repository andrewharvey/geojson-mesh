# geojson-mesh

Command line tool to extract shared borders of Polygons in a GeoJSON. See https://github.com/topojson/topojson-client#mesh

## Build

    npm install

## Command Line

    geojson-mesh [--explode] < input.geojson > output.geojson

If `--explode` is set, multiple features of geometry type `LineString` are created, otherwise a single feature of geometry type `MultiLineString` is created.
