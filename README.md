# Yohpal Mobile App

Short-form social video platform built with Flutter.

## Overview

Yohpal is a media-heavy social application focused on short-form video content, real-time engagement, and smooth user interactions. The app is designed to handle high-frequency user actions while maintaining consistent performance and responsiveness.

This repository contains the mobile client.

## Key Focus Areas

- Video feed architecture and pagination
- Media loading and playback optimization
- Real-time interactions and engagement flows
- Smooth animations and responsive UI
- Network resilience under variable connectivity

## Screenshots

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=12_Vgs0xbkrwMvPiXwoWSL0UxuYg8mhSM" width="250" />
  <img src="https://drive.google.com/uc?export=view&id=1IM9N8tdmL8joYbO6KXUphCiVAk9mzosL" width="250" />
  <img src="https://drive.google.com/uc?export=view&id=1QZxKVWrkv56Miqjv4lH7M16ce8jSpRQF" width="250" />
</p>

## Tech Stack

- Flutter (Dart)
- REST & real-time APIs
- Media streaming services
- Firebase (authentication and notifications)

## Architecture Notes

The app is structured around a modular feature-based architecture to isolate concerns such as:
- media playback
- feed state management
- user interactions
- networking and caching

Special attention is given to performance profiling and minimizing UI jank during scrolling and playback.

## Status

Production-ready / Actively maintained  
(Some backend services and credentials omitted)

## Notes

This project prioritizes real-world constraints such as bandwidth variability, device performance differences, and large media payloads.