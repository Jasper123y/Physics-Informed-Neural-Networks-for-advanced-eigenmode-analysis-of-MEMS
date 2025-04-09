# Physics-Informed-Neural-Networks-for-advanced-eigenmode-analysis-of-MEMS

This repository presents the implementation and experimental validation of a novel framework that leverages Physics-Informed Neural Networks (PINNs) for advanced eigenmode analysis of MEMS devices. Our work pushes the boundaries of MEMS modeling and simulation by integrating deep learning with physical principles, enabling accurate, efficient, and geometry-agnostic analysis of vibrational behavior in MEMS diaphragms.

We make three core contributions:

1. Multi-Mode PINNs Modeling: We successfully apply PINNs to compute multiple vibration modes in MEMS diaphragms with arbitrary geometries. This is achieved by embedding three key governing physical equations directly into the training process, enabling the model to inherently respect the physics of MEMS resonators.

2. Experimental Validation with DHM: The predictive capability of our framework is experimentally validated using Digital Holographic Microscopy (DHM) measurements on a fabricated Piezoelectric Micromachined Ultrasonic Transducer (PMUT) device. This validation confirms the model’s ability to capture real-world vibrational behavior with high fidelity.

3. Efficient Performance Evaluation Platform: We develop a computationally efficient platform that combines the predictive power of PINNs with traditional analytical models. This hybrid system allows rapid estimation of PMUT array performance metrics directly from geometric parameters, without the need for repeated full-scale simulations or finite element analysis (FEA).

Our results demonstrate that physics-informed learning can serve as a powerful alternative to conventional simulation methods for MEMS design, especially in scenarios involving non-standard geometries or where rapid evaluation is critical.

For implementation:

1. Model training, refer to file CNN (unet) for regression-orth6modes.ipynb
2. Prediction using H5 file, refer to file H5Prediction.ipynb
3. Trained models, refer to files regression_3phys_n_orth6modes.h5
4. Residual plotting, refer to plot_residuals.ipynb


