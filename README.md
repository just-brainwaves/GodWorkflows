# 🔥 Image Generation Workflows

Welcome to **my collection of advanced workflows for image generation using ComfyUI** — designed for high-quality, realistic, and anime-style outputs with smart automation features.

---

## ✨ Features

* 🔀 Random Prompt Combination Generator
* ⬆️ Upscale images up to **4x resolution**
* 📺 Supports high-resolution generation up to **1080p**
* 🧐 Realistic and consistent generations
* 🌺 Optimized sampler and model configurations for best results

---

## ⚙️ Requirements

* **Python 3.12** (Recommended)
* **ComfyUI**: See The Repo For Installation Instructions

---

## 📦 Custom Nodes (Place inside `ComfyUI/custom_nodes/`)

> All node-specific dependencies are mentioned in their respective repos/folders.
> ⚠️ **Use the same virtual environment (venv) or Python version that runs ComfyUI to avoid errors.**

* [ComfyUI Manager](https://github.com/Comfy-Org/ComfyUI-Manager.git)

  ```bash
  git clone https://github.com/Comfy-Org/ComfyUI-Manager.git custom_nodes/ComfyUI-Manager
  ```

* [ComfyUI Essentials](https://github.com/cubiq/ComfyUI_essentials.git)

  ```bash
  git clone https://github.com/cubiq/ComfyUI_essentials.git custom_nodes/ComfyUI_essentials
  ```

* [WAS Node Suite](https://github.com/WASasquatch/was-node-suite-comfyui.git)

  ```bash
  git clone https://github.com/WASasquatch/was-node-suite-comfyui.git custom_nodes/was-node-suite-comfyui
  ```

* [Flow Nodes](https://github.com/gitmylo/FlowNodes.git)

  ```bash
  git clone https://github.com/gitmylo/FlowNodes.git custom_nodes/FlowNodes
  ```

* *(Optional)* [ComfyUI Logic (for conditional calculations)](https://github.com/theUpsider/ComfyUI-Logic.git)

  ```bash
  git clone https://github.com/theUpsider/ComfyUI-Logic.git custom_nodes/ComfyUI-Logic
  ```

---

## 🧠 Resources

> For models, VAEs, LoRAs, Lycoris, embeddings, wildcards, and ControlNets:

* [civitai.com](https://civitai.com)
* [huggingface.co](https://huggingface.co)

---

## 🧪 Recommended Models per Workflow

* **🎨 Variated Anime Scene Generator**

  * Works best with: *Illustrious* or *Pony-based models* (Some SD1.5 models also perform well)

* **📸 Variated Realistic Generator**

  * Best with: *RealVisXL v5.0 Lightning (BakedVAE)*
  * Advanced option: *Flux.1D* or *Flux.1S* (for experienced users) As It Might Need Manual Configurations And Installations Of The Flux Libraries

* **👤 Variated Character Generator**

  * Designed for: *People Looking To Generate Variations In Their Workflows*

---
