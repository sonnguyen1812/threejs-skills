# Claude Code Plugin Usage

This repository ships a `.claude-plugin/` manifest and marketplace entry, allowing direct installation as a Claude Code plugin.

## Installation

### Method 1: Standard 2-Step Flow (Recommended for all versions)

**Inside Claude Code session:**
```bash
/plugin marketplace add sonnguyen1812/threejs-skills
/plugin install threejs-skills
```

**Or from Terminal:**
```bash
claude plugin marketplace add sonnguyen1812/threejs-skills
claude plugin install threejs-skills
```

---

### Method 2: One-Step Flow (Claude Code v2.1.275+)

**Inside Claude Code session:**
```bash
/plugin install threejs-skills --marketplace sonnguyen1812/threejs-skills
```

**Or from Terminal:**
```bash
claude plugin install threejs-skills --marketplace sonnguyen1812/threejs-skills
```

---

### Method 3: Local Plugin Directory

If you cloned this repository locally (e.g. to `D:\tools\threejs-skills`):

```bash
/plugin add D:\tools\threejs-skills
```

---

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
