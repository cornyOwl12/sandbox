# Vendored libraries

Copied here so Unicorn Run works without depending on a CDN.

- `three.module.min.js` from [three.js](https://threejs.org) r160 (MIT License, see `THREE-LICENSE`).
- `mediapipe/` from [@mediapipe/tasks-vision](https://www.npmjs.com/package/@mediapipe/tasks-vision) 0.10.14 (Apache License 2.0, Copyright Google LLC).

The pose model (`pose_landmarker_lite.task`) is downloaded at runtime from Google's public MediaPipe model storage.
