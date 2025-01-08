# DRTSF: Diverse Representations and Transformations for Time Series Classification
Diverse Representations Time Series Features (DRTSF) is a novel feature-based approach for time series classification (TSC) that integrates a rich set of representations, including derivatives, Hilbert transform, DWT, FFT, DCT, and autocorrelation. By transforming time series into a unified feature vector, DRTSF captures intricate patterns across multiple domains, enabling superior predictive performance.

Key Features:
- Comprehensive Representation: Combines diverse statistical, temporal, and spectral features into a cohesive feature set.
- State-of-the-Art Accuracy: Outperforms other feature-based methods and achieves results comparable to top-performing TSC models like Quant.
- Efficiency: One of the fastest TSC frameworks, matching the computational speed of leading methods.
- Robust Generalization: Performs well on datasets with complex structures, such as long sequences or large class counts.

Required Python Packages:
To run the code, ensure the following Python packages are installed:
- aeon
- PyWavelets
- dtaidistance
- tsfresh

Installation:
You can install all required packages using the following command:
pip install aeon PyWavelets dtaidistance tsfresh

Highlights:
- Evaluated on 142 datasets from the UCR archive using a consistent experimental framework.
- Implements a fast and scalable pipeline, making it suitable for large-scale and real-time TSC tasks.
- Provides insights into feature selection and optimization, allowing for further customization based on dataset-specific needs.

Some Results:

MCM for feature based methods and DRTSF:

![fig_mcm_fb](https://github.com/user-attachments/assets/08f6a4b5-2fc6-4816-87e5-5be216e5ea95)

MCM for state of the art and DRTSF:

![fig_mcm_sota](https://github.com/user-attachments/assets/3b1f733e-40c0-47c0-bfa4-12dcb5096203)
