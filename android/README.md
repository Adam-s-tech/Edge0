# edge0 — Android runtime

> ✅ Open-sourced on **2026-09-30**. This README will be updated with
> full build & usage docs together with the source drop.

The Android runtime runs the edge0 models fully on-device on Android
(Kotlin app + native inference engine): local streaming MoE inference
with the same recipe as the rest of the framework — SSD expert offload,
Recover-LoRA, and prerouter routing prediction.

The next milestone is the **unified inference framework** — one access
layer, runtime auto-adapting to the hardware platform (iOS / macOS /
Android / Windows / Python) — targeted for the **end of October 2026**;
see the [roadmap](../README.md#roadmap).

See the [repository README](../README.md) for the multi-platform picture.

---

> ✅ 源码已于 **2026-09-30** 开源，本 README 将随源码落库补全完整的构建
> 与使用文档。Android runtime：Kotlin App + 原生推理引擎的端侧推理。
> **统一推理框架**将于 **2026 年 10 月底**发布，详见
> [根 README 路线图](../README_zh.md)。
