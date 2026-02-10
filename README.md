# MAGIC: Motion-aware Gaussian Splatting in Dynamic CBCT Imaging

Author: Yufu Zhou, Hua Chen, Yi Liu, Ziheng Deng, Jun Zhao

This repository is the official implementation of MAGIC: Motion-aware Gaussian Splatting in Dynamic CBCT Imaging. 

The dynamic demos are available in [MAGIC](https://henryzyf.github.io/MAGIC/). The MP4 files can be downloaded from this repository.

**Abstract**:
Dynamic cone-beam computed tomography (CBCT) provides time-resolved visualization of respiratory motion, which is crucial for precise target localization in lung radiotherapy. While recent implicit neural representation (INR) methods have shown promise in modeling continuous spatiotemporal scenes, they are often computationally expensive. In this work, we propose a novel dynamic CBCT reconstruction framework, Motion-Aware Gaussian splatting In dynamic CBCT imaging (MAGIC), for accurate and efficient reconstruction. Instead of implicit neural networks, MAGIC represents the dynamic scene using learnable Gaussian primitives, which significantly reduces reconstruction time and maintains representation flexibility. We introduce a motion-aware decomposition (MADE) method for Gaussians to decouple static anatomical components and motion variations. The decomposition allows the network to focus its capacity on the deformation of dynamic regions, which facilitates more accurate motion modeling and shortens reconstruction time. Furthermore, we design a respiratory deformation network (RED) with an encoder of ten feature planes (Deca-Planes) to effectively capture inter- and intra-cycle similarities from quasi-periodic respiration. Experiments on simulated data, a physical phantom and clinical data demonstrate that compared to other methods, MAGIC achieves higher image quality and motion fidelity while accelerating reconstruction. These results indicate that MAGIC offers an effective and efficient alternative for dynamic CBCT imaging in the respiration-related radiotherapy.
