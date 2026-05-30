# TT-Metal: The Complete Reference

Live: **[maureranton.github.io/tt-metal-docs](https://maureranton.github.io/tt-metal-docs/)**

24 sections, 176 headings, 147 KB — everything about [Tenstorrent TT-Metal](https://github.com/tenstorrent/tt-metal). Beginners to experts.

**What's covered (every question a user could ask):**

Setup: 5 install methods, system requirements, emulation (tt-emule), after-unboxing flow, device naming, reset.  
Hardware: architecture deep-dive, WH/BH specs, pricing, buying guide, power/thermal, sub-devices, context limits.  
Programming: Metalium (SPMD/MPMD, kernels, CBs, fast dispatch, 151 API headers), end-to-end host code (Python + C++), PyTorch interop, format conversion, tensor introspection, ttnn vs tt_lib.  
TT-NN: 33 operation categories, attention (SDPA), collective comm (CCL), graph capture.  
Models: 50+ with benchmarks, launch commands for every model type, weight handling, BF4/BF8/FP8 quantization, 7-step porting guide, custom operator development.  
Training: TT-Train workflow, autograd/optimizers, TT-Blacksmith, mixed precision.  
Build/Test: CMake, code quality tools, pytest/GTest, 887 YAML configs.  
Ecosystem: TT-Forge quickstart, TT-XLA, TT-MLIR, TT-TVM, vLLM Plugin, pipeline parallelism (PP+TP+DP).  
Community: Discord, GitHub, contribution process, version management, bug report guide.  
Limitations: IEEE 754 gaps, hardware constraints, WH→BH porting, 8 performance anti-patterns, dynamic shapes.  
Comparison: TT-Metal vs CUDA (14 aspects), when to choose each.  
Debugging: 7 tools, 7 common errors with fixes, 3-step profiling, 9 first-run problems.  
Security: RISC-V sandbox model, isolation properties, attack surface map, model co-location warning.  
Reference: file type breakdown (20 extensions), 26 tech reports, complete glossary, bounty program.

Generated May 2026.
