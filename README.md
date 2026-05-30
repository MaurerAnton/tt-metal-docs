# TT-Metal: The Complete Reference

Live documentation: **[maureranton.github.io/tt-metal-docs](https://maureranton.github.io/tt-metal-docs/)**

A deep-dive reference covering everything about [Tenstorrent TT-Metal](https://github.com/tenstorrent/tt-metal) — 24 sections, 133 KB. Designed for absolute beginners through expert bounty hunters.

**Sections:**
1. Overview — what TT-Metal is
2. Setup — 4 install methods, requirements, emulation
3. After Unboxing — first-time flow, device naming, reset
4. Repository Statistics — exact file/line counts by language and module
5. Hardware Architecture — Tensix cores, RISC-V, NoC, tile computing
6. Hardware Specs & Pricing — WH/BH specs, prices, cloud, context limits
7. Buying Guide — which card, active vs passive, cables, decision matrix
8. Metalium SDK — low-level: kernels, circular buffers, SPMD, MPMD, fast dispatch
9. End-to-End Programming — complete Python and C++ host programs
10. PyTorch Interop — mixed execution, format conversion, ttnn vs tt_lib, root/concurrency/OOM/PCIe
11. TT-NN — high-level operator library, 33 categories
12. TT-Train — training framework, workflow, autograd/optimizers
13. Models — 50+ models with performance benchmarks
14. Running Models — launch commands, weights, quantization, model porting guide
15. Build System — CMake, build flags, code quality tools
16. Testing — pytest/GTest, 887 YAML configs, test directory structure
17. Tools & Debugging — 10 tools, graph capture, TT-NN Visualizer
18. Ecosystem — TT-Forge, TT-XLA, TT-MLIR, TT-TVM, vLLM Plugin, TT-Blacksmith
19. Community & Contributing — Discord, GitHub, contribution process, version management
20. Bounty Program — paid bounties, categories, workflow
21. File Type Breakdown — 20 extensions with exact counts
22. Technical Reports — 26 deep-dive reports available
23. Limitations & Known Issues — IEEE 754, hardware constraints, performance anti-patterns, dynamic shapes
24. TT-Metal vs. CUDA — 14-aspect comparison, when to choose which
25. Glossary — every term defined
26. Error Handling & Debugging — crash behavior, 7 tools, 7 common errors, profiling workflow
27. First-Run Troubleshooting — 9 common problems with cause and fix
28. Attack Surface — bounty hunter vulnerability mapping

Generated May 2026 from static analysis of the entire codebase.
