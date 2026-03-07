## Overview

deck.gl is a WebGL-powered framework for visual exploratory data analysis of large datasets. Created by Uber, it provides performant, GPU-accelerated rendering of massive datasets on top of maps.

## Core Features

- WebGL-powered rendering
- High-performance layer system
- Handles millions of data points
- 60 FPS rendering
- React integration
- Map-based and non-map visualizations
- Multiple coordinate systems
- Composable layers
- Custom layer development
- TypeScript support

## Built-in Layers

### Core Layers
- ScatterplotLayer - points
- LineLayer - lines between points
- ArcLayer - arcs between points
- PolygonLayer - filled polygons
- PathLayer - paths with width
- IconLayer - icons at points
- TextLayer - text labels
- GridLayer - grid heatmaps
- HexagonLayer - hexagonal binning

### Geo Layers
- GeoJsonLayer - GeoJSON features
- TileLayer - tiled maps
- TripsLayer - animated trips
- MVTLayer - Mapbox Vector Tiles
- TerrainLayer - 3D terrain
- Tile3DLayer - 3D tiles

### Aggregation Layers
- ScreenGridLayer - screen space grid
- CPUGridLayer - CPU aggregation
- HeatmapLayer - kernel density
- ContourLayer - contour lines

## 3D Capabilities

- 3D buildings
- 3D terrain
- 3D point clouds
- Elevation data
- Camera controls
- Lighting effects
- Shadow mapping

## Performance

- GPU-accelerated rendering
- Automatic data culling
- Level-of-detail support
- Viewport-based filtering
- Worker thread data processing
- Efficient updates
- Handles 10M+ points

## Interactions

- Hover and click events
- Tooltip support
- Picking (object selection)
- Brushing
- Filtering
- Viewport synchronization

## Map Integration

- Mapbox GL JS
- Google Maps
- Leaflet (via plugin)
- Custom base maps
- No-map mode

## Data Formats

- JSON
- GeoJSON
- CSV
- Arrow (Apache Arrow)
- Binary formats
- Streaming data

## Use Cases

- Geospatial data visualization
- Transportation analysis
- Urban planning
- IoT sensor data
- Flight paths visualization
- Real-time tracking
- Network visualization
- Scientific data visualization

## Pricing

Free and open-source under the MIT license.