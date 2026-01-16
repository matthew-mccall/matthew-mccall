## Hi — I'm Matthew 👋

I build low-level systems and embedded software, experiment with realtime graphics, and ship developer tooling. I prefer C++ for systems work and try to keep the projects I actively maintain small, focused, and well-tested.

Website: https://mmccall.dev · GitHub: https://github.com/matthew-mccall

## What I'm focused on (high-level)
- Systems & embedded C++: device tooling, memory management, and CMake-based builds.
- Realtime systems: engine experiments and realtime media when I have time to explore graphics.
- Dev tooling: small utilities and dotfiles to speed up daily work.

## Selected projects — highlights
I prioritize research and larger open-source contributions below; personal tooling at the end.

**Research & core systems work:**

- kokkos-memory-pool — device memory pool for Kokkos-backed code
  - https://github.com/matthew-mccall/kokkos-memory-pool
  - Low-level memory management for high-performance compute kernels; useful when you need predictable allocation behavior on devices.

- SCOREC/pcms — pcms (point localization & N-D search improvements)
  - https://github.com/SCOREC/pcms
  - I contributed point-search and higher-dimensional search improvements (2D→3D generalization, tolerances, refactoring) to the mesh query library.

**Larger open-source contributions:**

- SCOREC/omega_h — omega_h (Kokkos integration & memory-pool fixes)
  - https://github.com/SCOREC/omega_h
  - I contributed Kokkos integration, memory-pool fixes, and tests used by the adaptive mesh refinement library.

- open-algebra/Oasis — Oasis (CI, build, wasm tooling)
  - https://github.com/open-algebra/Oasis
  - I contribute CI and build improvements, documentation, and JS/wasm pipeline updates for the computer algebra system.

**Personal tooling & examples:**

- modern-cpp-dev — modern C++ examples and workshop material
  - https://github.com/matthew-mccall/modern-cpp-dev
  - Short, focused examples demonstrating modern C++ idioms and build patterns I use in teaching and small projects.

- mmccalldev — my personal site and notes (Astro)
  - https://github.com/matthew-mccall/mmccalldev
  - Source for my personal site; where I collect short posts, project snapshots, and documentation.

- Dockerfiles & dotfiles — development environment and helpers
  - https://github.com/matthew-mccall/Dockerfiles
  - https://github.com/matthew-mccall/dotfiles
  - Small, practical scripts and container setups for reproducible dev environments.

## How I work
- I prefer small, well-scoped repositories per project.
- For C++ systems work I use modern CMake, static analysis, and CI when possible.
- For embedded code I prioritize deterministic behavior, clear ownership of memory, and testability where hardware allows.

## Contact & links
- Website: https://mmccall.dev
- GitHub: https://github.com/matthew-mccall
- LinkedIn: https://linkedin.com/in/96d9