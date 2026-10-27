---
title: "GUI-Lens — Precise GUI Grounding via Coarse-to-Fine Cropping"
excerpt: "Training-free GUI grounding for off-the-shelf vision-language models. OCR and detected interface components provide coordinate references; iterative cropping refines the target before a click.<br/><a href='https://github.com/wangshirong123/GUI-Lens'>GitHub</a> · <a href='https://arxiv.org/abs/2608.03270'>Paper</a>"
collection: portfolio
---

**[GitHub](https://github.com/wangshirong123/GUI-Lens)** · **[Paper](https://arxiv.org/abs/2608.03270)**

GUI-Lens improves click localization on dense, high-resolution interfaces without additional model training. Coordinate Priming converts OCR text and detected UI components into position references for an off-the-shelf vision-language model.

The model selects progressively finer crops or proposes a click based on the instruction and current view. Crops and clicks are checked against the instruction, and accepted local click coordinates are mapped back to the original screen.

GUI-Lens is the visual grounding method associated with [GUI-Agent-Harness](/portfolio/2-gui-agent-harness). The repository provides the implementation and ScreenSpot-Pro evaluation instructions.
