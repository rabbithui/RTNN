# RTNN
This repository will host the official implementation of our paper: "**Processable Freeform Optical Lens Design Method Based on Differentiable Ray Tracing Neural Network Model**" (under review).
## Overview
Despite the exceptional light-field control capabilities of freeform surfaces, their inverse design based on source emission characteristics and desired beam distribution remains a challenging task, particularly in complex scenarios. We propose a novel self-supervised learning-based **ray tracing neural network (RTNN) for universal freeform surface design**. Unlike traditional methods, our framework:  
- RTNN is a dual-output architecture that co-optimizes optical performance and manufacturability through end-to-end physical-aware learning, establishing the first unified framework bridging computational optics and practical fabrication.
- We introduce an innovative SlopeLoss function to ensure manufacturability by preventing erratic curvatures.
- We successfully fabricate neural-designed freeform lenses, with optical experiments confirming the effectiveness of RTNN 
