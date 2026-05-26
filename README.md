# Hey, I'm Majkejl 👋

CS student with a focus on **graphics & GPU programming** — I like building things that run fast and look interesting. Currently wrapping up my bachelor's thesis on real-time ocean simulation using WebGPU.

- 🌱 Currently learning **WebGPU** and exploring GPU compute pipelines
- 🔭 Working on real-time simulation, volume rendering, and N-body physics
- 🌐 Portfolio (coming soon): [majkejl.github.io](https://majkejl.github.io)
- 💬 Discord: `@istilldontdousernames`
- 📫 Email: `misicek03@gmail.com`
<!--- - 🔗 LinkedIn: `<!-- your LinkedIn here -->`



---

## 🛠️ Tech Stack

**Languages**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL-5586A4?style=flat&logo=opengl&logoColor=white)

**Graphics & APIs**

![WebGPU](https://img.shields.io/badge/WebGPU-FF6D00?style=flat&logo=googlechrome&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat&logo=opengl&logoColor=white)
![Emscripten](https://img.shields.io/badge/Emscripten-000000?style=flat&logo=webassembly&logoColor=white)

**Tools & Build**

![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![Conan](https://img.shields.io/badge/Conan-6699CB?style=flat&logo=conan&logoColor=white)

---

## 🚀 Projects

### 🌊 [FFT Ocean Simulation](https://github.com/Majkejl/fft_water_sim)
> **Bachelor's thesis** — Real-time physically-based ocean surface simulation on the GPU

Built with **C++23 + WebGPU (WGSL)**, targeting both native desktop and the web via Emscripten. The ocean model uses the JONSWAP directional wave spectrum evolved each frame through a GPU-accelerated 2D Inverse FFT (Cooley-Tukey). Includes Jacobian-determinant foam, Fresnel reflections, cubemap skybox, and live ImGui parameter panels.

**[▶ Live Demo](https://majkejl.github.io/fft_water_sim.html)**

`C++23` `WebGPU` `WGSL` `Emscripten` `JONSWAP` `FFT`

<img width="426" height="240" alt="water" src="https://github.com/user-attachments/assets/ea3ef41d-0c1d-427e-994b-ec1c5d21ca30" />

---

### 🌌 [CUDA N-Body Galaxy Simulator](https://github.com/Majkejl/cuda-galaxy)
> Real-time 3D galaxy collision simulation — all-pairs O(N²) Newtonian gravity on the GPU

**CUDA + OpenGL** with zero CPU round-trips — particle positions are written directly into an OpenGL VBO via CUDA-OpenGL interop. Supports runtime toggling between a naive kernel and a shared-memory tiled kernel for live benchmarking. Two galaxies of ~16k–32k particles each.

`C++` `CUDA` `OpenGL` `GLSL` `N-Body` `GPU Compute`

*Status: In development*

<!-- 
  SCREENSHOT / GIF SECTION
  Recommended: a GIF is perfect here — galaxy collision spiral arms evolving over a few seconds is visually striking.
  Capture a 10–20s clip of the two galaxies merging and loop it.
  
  To add:
  ![CUDA Galaxy Simulator](screenshots/galaxy_demo.gif)
-->

---

### 🔬 [Volume Renderer](https://github.com/Majkejl/volume-renderer)
> Real-time GPU volume renderer — single-pass ray-casting through a 3D texture

Built in **C++17 / OpenGL 4.3 / GLSL**. Features single-pass ray-casting with front-to-back compositing, a transfer function with step-size-independent opacity, orbit camera, and slab-based box traversal. In progress: gradient-based Blinn-Phong lighting, interactive ImGui UI, and loading real cryo-EM datasets.

`C++17` `OpenGL 4.3` `GLSL` `Ray Casting` `Volume Rendering` `Conan`

*Status: In development*

<!-- 
  SCREENSHOT / GIF SECTION
  Recommended: once gradient lighting lands, a slow orbit around the rendered volume makes a great GIF.
  A static screenshot of the current synthetic volume works as a placeholder in the meantime.
  
  To add:
  ![Volume Renderer](screenshots/volume_demo.gif)
  
  Or static:
  ![Volume Renderer](screenshots/volume_static.png)
-->

---

## 📊 Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Majkejl&show_icons=true&theme=dark&hide_border=true&include_all_commits=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Majkejl&layout=compact&theme=dark&hide_border=true&langs_count=6" height="150" />
</p>

---

<p align="center">
  <sub>More projects coming soon · Screenshots & GIFs will be added as projects finish</sub>
</p>
