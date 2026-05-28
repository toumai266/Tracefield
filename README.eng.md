# Tracefield

[한국어](./README.ko.md)

## Overview

Tracefield is a geospatial AI workspace for analyzing regional change using Sentinel-2 satellite imagery. It combines satellite imagery, grid-based indicators, map context, and AI interpretation into a single analysis workspace designed to inspect before/after changes in a selected region.

## Key Features

- Before/after Sentinel-2 scene comparison
- Grid-based regional change analysis
- NDWI, NDVI, cloud, confidence, and change scoring
- Administrative boundary and nearby map-context integration
- Interactive map workspace
- Cell-level AI interpretation

## Tech Stack

- Frontend: Next.js, React, Three.js, MapLibre
- Backend: FastAPI, Rasterio, NumPy, Shapely
- AI: OpenAI Responses API
- Deployment: Docker Compose, Caddy

I designed and implemented this as an end-to-end prototype, covering the frontend workspace, backend analysis API, geospatial processing pipeline, and AI report integration.

## Notes

- Analysis results are observational aids and must not be used as official damage, legal, or safety determinations.
