<h1 align='center' style="text-align:center; font-weight:bold; font-size:2.0em; letter-spacing:2.0px;">WinSpot: A Windows GUI Grounding Benchmark with Multimodal Large Language Models</h1>

<!-- Authors -->
<p align="center">
    <a href="#" target="_blank" style="text-decoration: none;">Zheng Hui<sup>1,2</sup></a>&nbsp;,&nbsp;
    <a href="#" target="_blank" style="text-decoration: none;">Yinheng Li<sup>1</sup></a>&nbsp;,&nbsp;
    <a href="#" target="_blank" style="text-decoration: none;">Dan Zhao<sup>1</sup></a>&nbsp;,&nbsp;
    <a href="#" target="_blank" style="text-decoration: none;">Colby Banbury<sup>1</sup></a>&nbsp;,&nbsp;
    <a href="#" target="_blank" style="text-decoration: none;">Tianyi Chen<sup>1</sup></a>&nbsp;,&nbsp;
    <a href="#" target="_blank" style="text-decoration: none;">Kazuhito Koishida<sup>1</sup></a>
    <br/><br/>
    <sup>1</sup>Microsoft &nbsp;&nbsp;&nbsp;
    <sup>2</sup>Columbia University
</p>

<!-- Short warning / note if needed -->
<p align="center" style="color: red;">
    <b><em>Note: This repository and dataset are intended for research and benchmarking purposes only.</em></b>
</p>

---

<!-- Links (Paper, Project Page, Dataset) -->
<p align="center" style="font-size: 1.2em;">
    <b>
        <a href="https://arxiv.org/abs/2503.04730" target="_blank" style="text-decoration: none;">[Paper]</a>
    </b>
    &nbsp;&nbsp;
    <b>
        <a href="#" target="_blank" style="text-decoration: none;">[Project Page]</a>
    </b>
    &nbsp;&nbsp;
    <b>
        <a href="#" target="_blank" style="text-decoration: none;">[Dataset]</a>
    </b>
</p>

<div align="center">
    <img src=""asset/example.png"" alt="WinSpot Example" width="600">
    <p style="text-align: center; font-style: italic;">WinSpot flow and example, highlighting GUI elements.</p>
</div>

---

## Overview

**WinSpot** is the first large-scale benchmark dedicated to **Windows GUI grounding**, a crucial step for GUI automation and agent-based interaction with desktop applications. Unlike existing datasets that focus on structured, web- or mobile-based UI elements, WinSpot bridges the gap by providing thousands of **human-validated** screenshots and instruction-coordinate pairs from Windows applications. 

**Key features:**
- **Diverse, Real-World Screenshots:** Curated from Windows applications, including productivity software, system utilities, and more.  
- **Human-Validated Annotations:** Over **5,000** refined coordinate-instruction pairs across different Windows tasks.  
- **Two-Way Task Evaluation:** WinSpot supports both forward (locate UI element by instruction) and reverse (describe an element from a coordinate) grounding tasks.  
- **Extensible Framework:** Simple integration for adding new Windows GUI screenshots and instructions.

---

## News
-WinSpot will be released soon, stay tuned.

---


## Citation

If you find **WinSpot** helpful in your research or applications, please include the following reference in your work:
```bibtex
@misc{hui2025winclickguigroundingmultimodal,
title = {WinClick: GUI Grounding with Multimodal Large Language Models},
author = {Zheng Hui and Yinheng Li and Dan Zhao and Tianyi Chen and Colby Banbury and Kazuhito Koishida},
year = {2025}, eprint = {2503.04730}, archivePrefix = {arXiv},
primaryClass = {cs.CL}, url = {https://arxiv.org/abs/2503.04730}}
```
