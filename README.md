<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:0369a1&height=180&section=header&text=TheAdkk&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Rust%20%7C%20TypeScript%20%7C%20Python&descAlignY=55" alt="header" />
</div>

<h1 align="center">Hey, I'm Oswaldo Cruz (TheAdkk)</h1>

<p align="center">
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=0EA5E9&center=true&vCenter=true&width=560&height=45&lines=Rust+%7C+TypeScript+%7C+Python;Trading+systems+%26+market+tooling;romaco-mcp+%E2%80%94+AI+agents+on+the+chart;dalia+%E2%80%94+audio-reactive+visuals" alt="Typing SVG" />
</p>

<p align="center">
<a href="https://github.com/TheAdkk?tab=followers"><img alt="Followers" src="https://img.shields.io/github/followers/TheAdkk?style=for-the-badge&logo=github&label=Followers"></a>
<a href="https://github.com/TheAdkk"><img alt="Profile Views" src="https://komarev.com/ghpvc/?username=TheAdkk&style=for-the-badge&color=0ea5e9"></a>
</p>

<p align="center">
<a href="https://www.linkedin.com/in/oswaldoromancruz/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

## About me
- I love building interactive projects with a strong visual identity.
- I am fascinated by trading and systems thinking.
- I work with Python for automation and tooling.
- I also build with Astro for fast web experiences.

## Featured work
- [dalia](https://github.com/TheAdkk/dalia) - Audio-reactive visualizer with a Rust/WASM core and a TypeScript frontend.
- [romaco-mcp](https://github.com/romaco-labs/romaco-mcp) - MCP server that gives AI agents deterministic technical-analysis tools and draws the thesis onto a live romaco-charts chart.

## Stack
<p>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Astro-FF5D01?style=flat-square&logo=astro&logoColor=white" alt="Astro" />
</p>

## Metrics
<p align="center">
<img src="github-metrics.svg" alt="Metrics" />
</p>

<!-- ===========================================================================
GARAGE / 3D MODEL - parked until the new model lands

GitHub renders a fenced ```stl block as a REAL interactive 3D viewer, right here
in the profile README (drag to rotate, scroll to zoom). Verified end to end.
To switch it on: uncomment the heading below and paste ASCII STL inside the block.

## Garage

<sub>Drag to rotate. Scroll to zoom.</sub>

```stl
solid car
  ... paste ASCII STL facets here ...
endsolid car
```

--- HARD-WON NOTES, do not relearn these ---

1. EXPORT AS GLB. Never OBJ. The 3D-ripper OBJ converter drops node transforms:
   proportions came out 0.69 width/length vs 0.47 real, and the mesh arrived as
   4331 disconnected shards that no decimator can collapse (floors at 18k faces).
   GLB/glTF keeps transforms + material names. GLB is one self-contained file.

2. DROP THE INTERIOR. Filter out every material whose name starts with "INT_"
   (exact prefix - careful, a substring match on "INT" also eats CARPA-INT).
   On the Huracan that was ~79k of 209k triangles: dashboard, cables, seats,
   alcantara, even the RPM LCD. All invisible from outside.

3. BUDGET. ASCII STL costs ~135 bytes per face at 2 decimals.
   ~700 faces  = 92 KB   wing floats, struts gone
   ~1200 faces = 158 KB  wing WITH struts + mirrors  <- sweet spot
   ~2000 faces = 265 KB  splitter and wheels defined
   Rendering was only ever verified at 627 bytes. Large sizes are untested.

4. IF IT WONT DECIMATE: weld vertices, then voxelize (trimesh .voxelized(pitch)
   -> .fill() -> .marching_cubes) to force one watertight shell, then simplify.
   Only needed for shredded rips. A clean model should decimate directly.

5. STL HAS NO COLOR. Always solid grey. For a yellow car you need a rendered GIF
   or a real viewer on TheAdkk.github.io instead.

6. Z IS UP in the GitHub viewer. glTF here already had Z up; the OBJ needed a
   +90deg rotation about X.
============================================================================ -->

## Contact
- Email: oswaldo@romaco.io
- LinkedIn: https://www.linkedin.com/in/oswaldoromancruz/

<!-- profile-refresh: 2026-04-07 -->
