# My AI Setup

## The hardware

- **CPU:** AMD Ryzen 7 9800X3D
- **GPU:** 2× NVIDIA GeForce RTX 3090 24 GB (ASUS ROG Strix + MSI SUPRIM X) — 48 GB VRAM total
- **RAM:** 128 GB DDR5-5600 (2× 64 GB, dual channel)
- **Motherboard:** Gigabyte B850 AI TOP
- **Storage:** Samsung 990 EVO Plus 4 TB NVMe

## The inference and model

Just use Strata with `Qwen3.8-Flash-Next`. Quant IQ3_S. With some VM's and normal usage 120GB are used. I use Windows.

- Clone [Niko1221/Strata](https://github.com/Niko1221/Strata)
- Double-click `START-HERE.bat`
- Follow the steps. It'll download the model and required files.
- Update later with `UPDATE.bat`.

## The harness

Just use [OpenCode](https://github.com/anomalyco/opencode) with [`opencode.json`](opencode.json).

### Web search

OpenCode websearch is disabled because using SearXNG is better for this. Have your own instance and use it — easiest is Docker: [searxng/searxng-docker](https://github.com/searxng/searxng-docker).

MCP is [mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng). MCP config per repo or global. I prefer per repo to save as much context as I can.
