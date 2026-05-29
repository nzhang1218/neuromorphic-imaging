# Code

> **Code will be available after final publication.**

The source code for the neuromorphic imaging and tracking pipeline — including the dynamic vision sensor (DVS) event preprocessing, the spiking neural network model (Object Tracking Module, Object Reconstruction Module, and Residual Refinement Module), and the training / inference scripts — will be released here once the manuscript is published.

Planned contents of this directory upon release:

- Event preprocessing and temporal binning (`[p, t, x, y]` → `[T, C, H, W]` tensors)
- SNN model definitions (LIF neurons, stateful synapse filters, ORM / RRM / OTM modules)
- Training scripts and configuration files
- Inference / evaluation scripts (SSIM, MSE, tracking error)
- Pre-trained model weights
- Environment specification and setup instructions

The model was developed and trained on a single **NVIDIA RTX 3090** (~6 minutes per epoch; full 18-step sequence inference in under 15 ms).

⭐ **Star or watch the [repository](https://github.com/nzhang1218/neuromorphic-imaging) to be notified when the code is released.**

For questions in the meantime, contact **Ning Zhang** — ning_zhang1@brown.edu.
