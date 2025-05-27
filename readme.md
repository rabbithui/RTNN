# Processable Freeform Optical Lens Design via Differentiable Ray Tracing Neural Network  

*Code repository for the paper:  
**"Processable Freeform Optical Lens Design Method Based on Differentiable Ray Tracing Neural Network Model"***  
*(Under review, code will be released upon acceptance)*  

---

## 🔍 Overview  
We propose a **self-supervised Ray Tracing Neural Network (RTNN)** for universal freeform optical surface design. Unlike traditional methods, our framework:  
✅ Unifies **optical performance optimization** and **manufacturability constraints** in an end-to-end differentiable model.  
✅ Introduces **SlopeLoss**, a novel loss function to enforce fabrication-friendly curvature continuity.  
✅ Achieves **high adaptability** across diverse irradiance targets (simulations & experiments).  

**Key Innovations**:  
- Dual-output architecture: Ray-tracing channel (optical optimization) + Freeform surface prediction channel.  
- First differentiable model to jointly optimize optical efficiency and CNC-machinable surfaces.  
- Enables rapid deployment for illumination, imaging, and laser beam shaping applications.  

---

## 🚧 Repository Status  
| Component          | Status               |  
|--------------------|----------------------|  
| Code Implementation | 🔒 *Pending acceptance* |  
| Pre-trained Models  | 🔜 Coming soon       |  
| Example Datasets    | 🔜 Coming soon       |  

---

## 📂 Future Release Plan  
- [ ] Full PyTorch/TensorFlow implementation  
- [ ] Jupyter notebooks for custom design tasks  
- [ ] Optical simulation benchmarks  

---

## 📜 Citation  
If you find our work useful, please cite:  
```bibtex  
@article{rtnn2024,  
  title={Processable Freeform Optical Lens Design Method Based on Differentiable Ray Tracing Neural Network Model},  
  author={Your Name et al.},  
  journal={Under Review},  
  year={2024}  
}  