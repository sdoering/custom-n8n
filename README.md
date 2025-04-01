# Custom n8n Docker Image

This repository contains a custom n8n Docker image that extends the official n8n image with additional packages and configurations.

## Features

- Based on the official n8n Docker image
- Added `npx` globally for executing Node.js packages
- Configured health check to ensure container stability

## Usage

### Pull from GitHub Container Registry

```bash
docker pull ghcr.io/sdoering/n8n-custom:latest