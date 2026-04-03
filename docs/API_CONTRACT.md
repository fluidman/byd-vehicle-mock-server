# API Contract

## Purpose

This document defines the mock API used by `hass-byd-vehicle-plus` in mock mode.

## Initial endpoint groups

- auth
- vehicles
- realtime
- gps
- hvac
- charging
- energy
- commands
- capabilities

## Design goals

- stable JSON contract
- predictable scenario switching
- vehicle-profile-driven capabilities
- easy local deployment via Docker
