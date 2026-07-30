# vto-app

A **Virtual Try-On (VTO)** application for eyewear — planned to let users try on glasses/frames in real time using webcam-based face tracking and 3D model rendering.

## Status

This repository is in its initial planning stage. No application source code has been committed yet. The only functional content currently in the repo is a GitHub Actions workflow (`.github/workflows/add-vto-todos.yml`) that seeds a project board with the Sprint 1 backlog via the GitHub API.

## Planned scope

Based on the Sprint 1 backlog defined in the repo's automation workflow, the intended feature set is:

- Base React project structure
- Three.js integration for loading and rendering 3D frame models (`.glb`)
- Real-time face tracking using MediaPipe FaceMesh
- Binding the 3D frame model to detected face landmarks
- UI for selecting between different eyewear frames
- Camera input handling (webcam capture)
- Model scaling/rotation smoothing for a stable try-on experience
- Performance testing and rendering optimization

## Planned tech stack

- **React** — UI framework
- **Three.js** — 3D rendering of frame models
- **MediaPipe FaceMesh** — face landmark detection for try-on positioning
- **GitHub Actions** — repo/project automation (sprint backlog creation)

## Getting started

No build or run instructions exist yet, as application code has not been added. This section will be updated once the base project (React + Three.js) is scaffolded.

## Contributing

Sprint 1 tasks are tracked on the repository's GitHub Project board. The `Add VTO Sprint 1 To-Dos` workflow (manually triggered) creates these issues and adds them to the board automatically.
