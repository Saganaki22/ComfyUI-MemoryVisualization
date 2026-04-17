# ComfyUI Memory Visualization

Real-time VRAM and memory monitoring panel for ComfyUI.

When [aimdo](https://github.com/aimdo-ai/ComfyUI-aimdo) is enabled, also shows per-model page-level residency heatmaps and watermark controls.

https://github.com/user-attachments/assets/25177b46-7631-4d3f-97f9-4ffae7eea24c

## Installation

Clone into your `custom_nodes` folder:

```
git clone https://github.com/Saganaki22/ComfyUI-MemoryVisualization ComfyUI/custom_nodes/ComfyUI-MemoryVisualization
```

## Fork extras

This fork ([Saganaki22/ComfyUI-MemoryVisualization](https://github.com/Saganaki22/ComfyUI-MemoryVisualization)) adds the following on top of [upstream](https://github.com/kijai/ComfyUI-MemoryVisualization):

- **Customizable hotkey to reset panel position** — Right-click the panel to open a context menu where you can rebind the reset-position hotkey (default: `Home`). Useful if you drag the panel off-screen.
