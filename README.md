# My AI Setup

- **CPU:** AMD Ryzen 7 9800X3D
- **GPU:** 2× NVIDIA GeForce RTX 3090 24 GB (ASUS ROG Strix + MSI SUPRIM X) — 48 GB VRAM total
- **RAM:** 128 GB DDR5-5600 (2× 64 GB, dual channel)
- **Motherboard:** Gigabyte B850 AI TOP
- **Storage:** Samsung 990 EVO Plus 4 TB NVMe

I use Windows. Just use Strata with `Qwen3.8-Flash-Next`. Quant IQ3_S. With some VM's and normal usage 120GB are used.

- Clone [Niko1221/Strata](https://github.com/Niko1221/Strata)
- Double-click `START-HERE.bat`
- Follow the steps.
- Update later with `UPDATE.bat`.

## Agent — OpenCode

Uses [`opencode.json`](opencode.json) from this repo: local provider pointing at the Strata endpoint, `model: local/Qwen3.8-Flash-Next-IQ3_S`.

## Web search — SearXNG

OpenCode websearch is disabled because using SearXNG is better for this. Have your own instance and use it.

MCP config per repo or global. I prefer per repo to save as much context as I can.
