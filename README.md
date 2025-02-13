# Video Streaming with Multiple Resolutions using Docker

This project enables video streaming in multiple resolutions using **Docker containers**. It utilizes **FFmpeg** to transcode videos into adaptive bitrate streaming format (HLS) and serves the content using **NGINX**, making it accessible across the entire network.

## Features
- **Multi-resolution streaming** (360p, 720p) using **FFmpeg**
- **Dockerized setup** for easy deployment
- **NGINX-based HLS streaming** for serving video content
- **Local network accessibility** for seamless video playback

## Prerequisites
- **Docker & Docker Compose** installed

## Configuration
- Modify `nginx.conf` to adjust streaming settings.
- Change FFmpeg command in `docker-compose.yml` to include additional resolutions.

