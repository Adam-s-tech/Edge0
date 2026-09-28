# edge0 — Python framework

The Python implementation of the edge0 streaming MoE inference framework
(SSD expert offload + Recover-LoRA + prerouter routing prediction),
shipping the MLX backend for Apple Silicon.

This directory is one platform of the edge0 multi-platform repo — see the
[repository README](../README.md) for the full picture (macOS / iOS /
Android runtimes and the unified-framework roadmap).

## Quick start

```bash
python3.12 -m venv .venv && .venv/bin/pip install -e '.[dev,fetch]'
edge0 demo edge0-8b        # after downloading a model; see ../README.md
```

- Docs: [`docs/`](../docs/) at the repo root (architecture, attention, MoE, streaming, prerouter)
- Examples: [`examples/`](examples/) · Scripts: [`scripts/`](scripts/)
- Tests: `pytest` (unit) · `pytest -m slow` (real weights)

## License

Apache-2.0, including vendored third-party code (see [NOTICE](../NOTICE)).
