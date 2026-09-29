# Eurth Map Pipeline

This repository contains the GIS data, scripts, and tile generation pipelines used to produce and maintain the interactive maps for the [Eurth](https://eurth.org) worldbuilding community.

## Overview

The mapping workflow leverages a combination of cartographic tools to process high-resolution raster maps, project them correctly, and slice them into web-friendly tile sets for spatial exploration.

- **Projection & Transformation:** Managed via tools like G.Projector.
- **Spatial Processing & Tiling:** Processed using MapTiler
- **Automation:** Includes local helper scripts (e.g., Automator workflows) to streamline the tile generation and rendering process.

## Repository Structure

```text
├── data/           # Raw and processed spatial source files
├── scripts/        # Python scripts, GDAL commands, and automation workflows
├── tiles/          # Generated map tile outputs (or configuration for generation)
└── README.md
```

## Workflow

1. Source Preparation: Master raster artwork is prepared and aligned.
2. Projection Conversion: Custom projections are applied and calibrated using G.Projector.
3. Tile Generation: GDAL tiling processes are executed via QGIS/command-line scripts to slice the map into multi-resolution web tiles.

## License

This project is maintained for the Eurth.org community. Please check with the repository owner before reusing assets outside of the Eurth project.
