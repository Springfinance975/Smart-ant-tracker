# Smart Ant Tracker Tile

A Year 9 physics/technology prototype for monitoring ant-colony conditions with an ESP32 sensor tile and companion PWA.

## Project structure

- `apps/companion-app` — mobile-first companion app prototype
- `services/api` — small readings/alerts/export API
- `firmware/esp32` — ESP32 sensor firmware scaffold
- `packages/shared` — shared data contracts
- `data` — clearly labelled demo data and analytics
- `docs` — research and system documentation
- `deployment` — deployment placeholders
- `.github/workflows` — basic checks

> **Demo-data notice:** readings in this repository are prototype/demo values unless explicitly marked as hardware measurements.

## Core physics

The project investigates environmental variables such as temperature, humidity, light and activity, and how sensor data can be converted into useful information. The ESP32 is the proposed data-acquisition device.

## Status

Prototype scaffold — ready for implementation and classroom demonstration.
