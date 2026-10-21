# Claude Code Plugin Usage

This repository ships a `.claude-plugin/` manifest and marketplace entry, allowing direct installation as a Claude Code plugin.

## Install

### From Marketplace (One-step)

In Claude Code (v2.1.275+):

```bash
/plugin install threejs-skills --marketplace sonnguyen1812/threejs-skills
```

### Local Plugin Directory

If you cloned this repository locally (e.g. to `D:\tools\threejs-skills`):

```bash
/plugin add D:\tools\threejs-skills
```

## Included Skills

Targets **Three.js r186** and **React Three Fiber 9.8** across 13 modular skills under `skills/`:
- `threejs-fundamentals`
- `threejs-geometry`
- `threejs-materials`
- `threejs-lighting`
- `threejs-textures`
- `threejs-animation`
- `threejs-loaders`
- `threejs-shaders`
- `threejs-postprocessing`
- `threejs-interaction`
- `threejs-performance`
- `threejs-react-three-fiber`
- `threejs-asset-pipeline`
