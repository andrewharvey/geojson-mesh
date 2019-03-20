# geojson-mesh

Command line tool to extract borders of GeoJSON Polygons into a non-overlapping set of LineString's. See https://github.com/topojson/topojson-client#mesh

## Build

    npm install

## Command Line

    geojson-mesh [--explode] < input.geojson > output.geojson

If `--explode` is set, multiple features of geometry type `LineString` are created, otherwise a single feature of geometry type `MultiLineString` is created.
