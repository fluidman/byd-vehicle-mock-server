# Architecture

## Overview

This project is a standalone emulator backend intended for use with `hass-byd-vehicle-plus` mock mode.

## Design principles

- keep Home Assistant specific logic out of the mock server
- expose a stable JSON contract for the integration
- support profile-driven capabilities
- support scenario-driven state simulation
- be easy to run locally with Docker

## Core building blocks

- API layer
- vehicle profile loader
- scenario/state engine
- command handling
- fixture storage
