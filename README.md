# Multimodal Iterative LLM Solver (MILS) with DeepFloyd IF

## 🚀 Overview  
In recent years, the demand for intelligent systems capable of understanding and generating content across multiple modalities has grown significantly.  
This project addresses the challenge of **cross-modal retrieval**, specifically focusing on generating **high-quality images from textual descriptions**.  

Traditional text-to-image models (e.g., **Latent Diffusion Models - LDMs**) often suffer from:  
- Poor semantic alignment  
- Limited resolution  
- Inadequate visual fidelity  

To overcome these limitations, this work integrates the **DeepFloyd IF** model—a state-of-the-art pixel-space diffusion model—into a modular retrieval framework.  

---

## ✨ Key Features  
- **Multimodal Iterative LLM Solver (MILS):**  
  - Uses **LLaMA** as a text generator  
  - Employs **CLIP/ImageBind** as scorers for iterative refinement  
  - Produces **precise intermediate captions**  

- **DeepFloyd IF Integration:**  
  - Generates **high-resolution images** from refined captions  
  - Maintains **text-image coherence** and **semantic alignment**  

- **Robust Evaluation Metrics:**  
  - **FID Score** for visual quality  
  - **CLIP Score** for semantic consistency  

---

## 🏗️ System Architecture  

