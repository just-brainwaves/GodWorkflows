# 🔥 Image Generation Workflows

Welcome to **my collection of advanced workflows for image generation using ComfyUI** — designed for high-quality, realistic, and anime-style outputs with smart automation features.

---

## ✨ Features

* 🔀 Random Prompt Combination Generator

* 🔀 Dynamic LoRA Loader

* ⬆️ Upscale images up to **4x resolution**

* 📺 Supports high-resolution generation up to **1080p**

* 🧐 Realistic and consistent generations

* 🌺 Optimized sampler and model configurations for best results

---

## 🖼️ Screenshots

> Below are sample screenshots of the workflows in action:

### 🧬 The Wilrcard Processor To Generate Random Or Customised Variations


### 🏞️ Realistic Image Generation Workflow

### 🖌️ Anime Scene Generation Workflow

---

## ⚙️ Requirements

* **Python 3.12** (Recommended)

### 🔼 Recommended Upscale Models

* 4x-AnimeSharp (for anime-style images)
* RealESRGAN\_x4plus (for general upscaling)
* 4x-UltraSharp  (for high detail enhancement)

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

* ComfyUI-Custom-Scripts & ComfyUI-Impact-Pack From The ComfyUi-Manager

---

## 🧠 Resources

> For models, VAEs, LoRAs, Lycoris, embeddings, wildcards, and ControlNets:

* [civitai.com](https://civitai.com)
* [huggingface.co](https://huggingface.co)

---

## 🧪 Recommended Models per Workflow

* **🎨 Variated Anime Scene Generations**

  * Works best with: *Illustrious* or *Pony-based models* (Some SD1.5 models also perform well)

* **📸 Variated Realistic Generations**

  * Best with: *RealVisXL v5.0 Lightning (BakedVAE)* Or *Juggernaut XL* Or Any Other Well Trained Stable Diffusion Model
  * Advanced option: *Flux.1D* or *Flux.1S* (for experienced users) as it might need manual configurations and installations of the Flux libraries

---

*Make sure to place your screenshots inside a ******************************`screenshots/`****************************** folder in your repo directory.*
