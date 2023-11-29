# tree-flatgeobuf-demo

## create flatgeobuf file
ogr2ogr -f FlatGeobuf filename.fgb filename.geojson

## serve flatgeobuf file
python -m http.server

cd src

localhost:8000