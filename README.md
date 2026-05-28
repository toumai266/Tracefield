# Tracefield

[한국어](./README.ko.md)

Tracefield is a portfolio case study for a geospatial AI workspace that analyzes regional change using Sentinel-2 satellite imagery.

This repository contains project introduction materials only. Source code, deployment files, environment files, and internal implementation assets are not included.

## Overview

Tracefield was designed to help inspect regional change by combining satellite imagery, grid-based indicators, map context, and AI-assisted interpretation in a single analysis workspace.

## Key Features

- Before/after Sentinel-2 scene comparison
- Grid-based regional change analysis
- NDWI, NDVI, cloud, confidence, and change scoring
- Administrative boundary and nearby map-context integration
- Interactive map workspace
- Cell-level AI interpretation

## Screenshots

Screenshots will be added under [`screenshots`](./screenshots).

Recommended set:

- Main workspace
- Before/after scene comparison
- Grid analysis view
- Cell-level AI interpretation panel

## Tech Stack

- Frontend: Next.js, React, Three.js, MapLibre
- Backend: FastAPI, Rasterio, NumPy, Shapely
- AI: OpenAI Responses API
- Deployment: Docker Compose, Caddy

## Project Scope

This was built as an end-to-end prototype covering the product flow, frontend workspace, backend analysis API, geospatial processing pipeline, and AI report integration.

## Notes

- This repository is for portfolio review only.
- Source code and deployment configuration are intentionally excluded.
- Analysis results are observational and are not official damage, legal, or safety determinations.
- No license is granted for reuse, redistribution, or commercial use.
