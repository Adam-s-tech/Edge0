# edge0 — Windows runtime

> ✅ Open-sourced on **2026-09-30**. This README will be updated with
> full build & usage docs together with the source drop.

The Windows runtime is a native C++17 port of the edge0 streaming core
(CMake build) with a **Vulkan** compute backend: the `edge0` core
(streaming mmap / cache / layer / MoE) is mirrored from the upstream
Python tree, running the same recipe as the rest of the framework — SSD
expert offload, Recover-LoRA, and prerouter routing prediction.

The next milestone is the **unified inference framework** — one access
layer, runtime auto-adapting to the hardware platform (iOS / macOS /
Android / Windows / Python) — targeted for **Q4 2026**; see the
[roadmap](../README.md#roadmap).

See the [repository README](../README.md) for the multi-platform picture.

---

> ✅ 源码已于 **2026-09-30** 开源，本 README 将随源码落库补全完整的构建
> 与使用文档。Windows runtime：edge0 流式核心的原生 C++17 移植（CMake
> 构建）+ **Vulkan** 计算后端，`edge0` 核心（streaming mmap / cache /
> layer / MoE）镜像自上游 Python 树，沿用同一套配方。**统一推理框架**
> 将于 **2026 Q4** 发布，详见[根 README 路线图](../README_zh.md)。
