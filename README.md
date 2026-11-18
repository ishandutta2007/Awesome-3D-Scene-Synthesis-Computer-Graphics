# Awesome-3D-Scene-Synthesis-Computer-Graphics

# Top 3D Scene Synthesis & Computer Graphics Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Generative 3D Scene Synthesis, Agentic Layout Evolution, Radiance Fields (3DGS/NeRF) & Real-Time Computer Graphics*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Scene Synthesis & Computer Graphics**. These tools generate complete, physically grounded 3D environments from single images or text prompts, reconstruct photorealistic 3D Gaussian Splatting scenes, optimize spatial layouts via VLM agents, and render interactive 3D worlds in real time.

**Examples** include Luma AI, Polycam, Scaniverse, Jawset Postshot, KIRI Engine, Gracia AI, Spline, Artec Cloud, Nerfstudio, SuperSplat, and rxjfighting/SceneMosaic (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for agentic 3D scene synthesis, single-image compositional scene generation, procedural world-building, local 3D Gaussian Splatting training/editing, and foundational computer graphics engines — ideal for graphics programmers, spatial AI researchers, game developers, and simulation engineers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Luma AI](https://lumalabs.ai)**  
  Cloud AI 3D capture and generative world platform converting videos and text prompts into photorealistic 3D Gaussian Splats, meshes, and interactive WebGL scenes.

- **[Polycam](https://poly.cam)**  
  Cross-platform mobile and web 3D scanning suite supporting cloud 3D Gaussian Splatting, LiDAR capture, photogrammetry, and browser-based scene sharing.

- **[Niantic Scaniverse](https://scaniverse.com)**  
  Mobile spatial scanning app offering on-device 3D Gaussian Splatting capture, scene editing, and geospatial world mapping without mandatory cloud uploads.

- **[Jawset Postshot](https://jawset.com)**  
  High-speed 3D Gaussian Splatting and radiance field workstation featuring live training previews, ACES color pipelines, and Unreal Engine / After Effects plugins.

- **[KIRI Engine](https://kiriengine.app)**  
  Cloud 3D scanning and Gaussian Splatting platform providing photo-to-3D reconstruction, splat-to-mesh conversion, quad-retopology, and Blender integration.

- **[Gracia AI](https://gracia.ai)**  
  Spatial computing platform for publishing, streaming, and experiencing photorealistic 6DoF volumetric 3D Gaussian Splatting scenes across VR headsets and web.

- **[Spline (3DGS & AI)](https://spline.design)**  
  Collaborative browser-based 3D design studio supporting imported 3D Gaussian Splats, generative 3D assets, real-time physics, and instant WebGL embeds.

- **[Artec Cloud](https://artec3d.com)**  
  Cloud-based 3D scan processing, point-cloud alignment, mesh reconstruction, and collaborative inspection platform engineered for precision 3D scanners.

- **[World Labs (Marble)](https://worldlabs.ai)**  
  Spatial intelligence SaaS platform generating persistent, explorable, 3D-consistent virtual worlds and interactive environments from single images or text prompts.


## Open-Source GitHub Projects

- **[rxjfighting/SceneMosaic](https://github.com/rxjfighting/SceneMosaic)**  
  Open-source framework ([Project Page](https://rxjfighting.github.io/SceneMosaic/)) that turns a single indoor photograph into a simulation-ready, editable 3D `.glb` scene via promptable segmentation (`SAM3`), per-object 3D reconstruction (`SAM 3D Objects`), and VLM-guided local unit layout evolution.

- **[Nerfstudio](https://github.com)**  
  Modular open-source (`Apache-2.0`) PyTorch framework unifying 3D Gaussian Splatting (`splatfacto`), NeRFs, COLMAP/GLOMAP pose estimation, and a real-time interactive web viewer.

- **[SuperSplat (PlayCanvas)](https://github.com)**  
  Free and open-source (`MIT`) browser-based 3D Gaussian Splatting editor and optimizer for inspecting, cropping, cleaning floaters, and compressing `.ply` / `.sog` scenes.

- **[HunyuanWorld-1.0 (Tencent)](https://github.com)**  
  Open-source generative 3D world and scene synthesis framework designed to create explorable, interactive 3D environments from text prompts or reference images.

- **[SceneGen](https://3dscenegen.github.io/)**  
  Open-source single-image 3D scene generation model synthesizing compositional 3D geometry, textures, and relative spatial asset placements in a single feed-forward pass.

- **[SceneWeaver](https://scene-weaver.github.io/)**  
  Open-source reflective agentic framework for all-in-one 3D scene synthesis combining an LLM planner with closed-loop visual/physical refinement and OpenUSD export for Isaac Sim.

- **[Infinigen & Infinigen Indoors (`princeton-vl/Infinigen`)](https://github.com)**  
  Princeton VL open-source (`BSD-3-Clause`) procedural 3D world and indoor scene generator built on Blender Geometry Nodes producing infinite photorealistic environments.

- **[Holodeck (`allenai/Holodeck`)](https://github.com)**  
  Open-source language-guided 3D embodied AI environment generator utilizing LLMs and Objaverse assets to synthesize diverse, physically valid interactive indoor scenes.

- **[InstructScene (`chenguolin/InstructScene`)](https://github.com)**  
  ICLR 2024 open-source instruction-driven 3D indoor scene synthesis model pairing a semantic graph prior with a layout decoder for controllable scene generation and editing.

- **[MIDI (`VAST-AI-Research/MIDI-3D`)](https://github.com)**  
  Open-source multi-instance diffusion framework for compositional 3D scene generation from a single image, simultaneously synthesizing multiple spatially aligned 3D objects.

- **[3D-RE-GEN (`cgtuebingen/3D-RE-GEN`)](https://github.com)**  
  Open-source (`MIT`) single-image indoor scene reconstruction pipeline integrating Grounded-SAM segmentation, generative inpainting, 3D asset synthesis (`Hunyuan3D-2.0`), and layout optimization.

- **[Original 3D Gaussian Splatting (`graphdeco-inria/gaussian-splatting`)](https://github.com)**  
  Reference SIGGRAPH 2023 open-source CUDA implementation for real-time radiance field synthesis and interactive SIBR scene rendering.

- **[Brush (`ArthurBrussee/brush`)](https://github.com)**  
  Cross-platform open-source (`Apache-2.0`) 3DGS training and rendering engine built in Rust with Burn and WebGPU—running natively across NVIDIA, AMD, Apple Silicon, Android, and web browsers.

- **[Blender](https://github.com)**  
  Flagship open-source (`GPL-2.0+`) 3D computer graphics creation suite featuring Geometry Nodes procedural scene synthesis, Cycles path tracing, and real-time EEVEE rendering.

- **[Three.js](https://github.com)**  
  Foundational open-source (`MIT`) JavaScript 3D graphics library powering browser-native WebGL/WebGPU scene composition, PBR shaders, and Gaussian Splat viewers.

### Additional Strong Open-Source Options

- **[hzxie/Awesome-3D-Scene-Generation](https://github.com/hzxie/Awesome-3D-Scene-Generation)** and **[YandanYang/Awesome-Indoor-Scene-Synthesis](https://github.com/YandanYang/Awesome-Indoor-Scene-Synthesis)** for comprehensive curated research indexes covering 300+ 3D scene synthesis papers, datasets (`3D-FRONT`, `HSSD`, `ScanNet`), and benchmarks.
- **[DirectLayout (`rxjfighting/DirectLayout`)](https://github.com/rxjfighting)** for direct numerical layout generation and spatial reasoning in 3D indoor scene synthesis.
- **[gsplat](https://github.com)** and **[LichtFeld Studio (`MrNeRF/LichtFeld-Studio`)](https://github.com)** for high-performance CUDA 3DGS rasterization and native C++ workstation scene editing.
- **[Microsoft TRELLIS](https://github.com)** and **[PartCrafter](https://github.com)** for structured latent 3D asset and compositional part-level mesh synthesis used inside multi-object scene pipelines.
- **[Babylon.js](https://github.com)** and **[Godot Engine](https://github.com)** for open-source real-time WebGPU/WebGL and desktop 3D computer graphics runtimes.

**Frameworks for building custom systems**: Combine **rxjfighting/SceneMosaic** or **SceneWeaver** with **HunyuanWorld-1.0**, **Nerfstudio (`gsplat`)**, **Blender**, and **Three.js / SuperSplat** for end-to-end open-source 3D scene synthesis and computer graphics pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agentic and multi-object 3D scene synthesis pipelines (such as `SceneMosaic` and `SAM 3D Objects`) require high-VRAM NVIDIA GPUs (24GB–38GB+) and access approval for gated Hugging Face foundation weights.
- Verify individual software, dataset, and model weight licenses (`MIT`, `Apache-2.0`, `BSD-3-Clause`, `GPL-2.0+`, or research-only terms) before commercial deployment.

---

**Made for computer graphics programmers, spatial AI researchers, 3D environment artists, and simulation engineers.**  
Let's make 3D scene synthesis and computer graphics more open, physically grounded, and reproducible.
