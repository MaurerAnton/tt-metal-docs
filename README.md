# TT-Metal: The Complete Reference

Live documentation: **[maureranton.github.io/tt-metal-docs](https://maureranton.github.io/tt-metal-docs/)**

A deep-dive reference covering everything about the [Tenstorrent TT-Metal](https://github.com/tenstorrent/tt-metal) open-source SDK — 23 sections, 122 KB, designed for absolute beginners through expert bounty hunters.

**Sections:**
1. Overview — what TT-Metal is
2. Setup — 4 install methods, system requirements, emulation (tt-emule)
3. After Unboxing — first-time setup flow, device naming reference, device reset
4. Stats — exact file/line counts by language and module
5. Hardware Architecture — Tensix cores, RISC-V, NoC, tile computing
6. Hardware Specs & Pricing — Wormhole/Blackhole specs, prices, cloud, context limits
7. Buying Guide — which card for which use case, active vs passive, cables
8. Metalium SDK — low-level programming, kernels, circular buffers
9. End-to-End Programming — complete Python and C++ host programs, SPMD
10. PyTorch Interop — mixed execution, format conversion, memory layout, ttnn vs tt_lib
11. TT-NN — high-level operator library, 33 operation categories
12. TT-Train — training framework overview
13. Models — 50+ models with performance benchmarks
14. Running Models — launch commands, weight handling, quantization (bfp4/bfp8/fp8)
15. Build System — CMake, build flags, code quality tools
16. Testing — test directory structure, pytest/GTest, 887 YAML configs
17. Tools & Debugging — TT-NN Visualizer, Tracy, Watcher, DPRINT
18. Community & Contributing — Discord, GitHub, contribution process, version management
19. Bounty Program — paid bounties for open-source contributions
20. File Type Breakdown — 20 file extensions with counts
21. Technical Reports — 26 deep-dive reports available
22. Limitations & Known Issues — IEEE 754 gaps, hardware constraints, precision tradeoffs
23. TT-Metal vs. CUDA — 14-aspect comparison
24. Glossary — every term explained
25. Error Handling & Debugging — crash behavior, 7 tools, 7 common errors, profiling workflow
26. First-Run Troubleshooting — 9 common problems with causes and fixes
27. Attack Surface — bounty hunter vulnerability mapping

Generated May 2026 from static analysis of the entire codebase.
