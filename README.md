# la-map

**la-map** is a Leaflet map for visualizing railway infrastructure based on OpenStreetMap (OSM) data, particularly focused on routes tagged with `ref:La`.
The application leverages integrates data from the Overpass API to display detailed railway line information.

## Features

- **Interactive Map**: Explore railway routes with zoom and pan functionality.
- **OpenRailwayMap Layers**:
    - Infrastructure view
    - Speed limits view
- **Railway Details**: Click on a route to view detailed information, such as:
    - Route reference (`ref:La`)
    - Name and operator
- **Dynamic Coloring**: Each route is uniquely colored based on its `ref:La` attribute for easy differentiation.

## Data Source

The application fetches data dynamically from the [Overpass API](https://overpass-api.de/) and uses the `ref:La` key from OpenStreetMap.
This key is documented on the [OSM Wiki](https://wiki.openstreetmap.org/wiki/Key:ref:La).

## Dependencies

- [Leaflet](https://leafletjs.com/): Map rendering library
- [Overpass API](https://overpass-api.de/): OSM query service
- [OpenRailwayMap](https://www.openrailwaymap.org/): Railway-specific map layers

## Contributions

Contributions are welcome! Feel free to submit issues or pull requests to enhance the functionality or fix bugs.

## License

This project is licensed under the CC0 License. See the `LICENSE` file for more details.

## Acknowledgments

- [OpenStreetMap Contributors](https://www.openstreetmap.org/)
- [OpenRailwayMap](https://www.openrailwaymap.org/)

