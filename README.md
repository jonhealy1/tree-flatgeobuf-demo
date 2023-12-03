# tree-flatgeobuf-demo

## create flatgeobuf file
ogr2ogr -f FlatGeobuf filename.fgb filename.geojson

## serve flatgeobuf file
cd src
python -m http.server

localhost:8000