# MultiscaleElasticWovenNeuralNet
The original data bases and codes related to "A multiscale deep learning model for elastic properties of woven composites"

Collabrators: Ehsan Ghane, Martin Fagerström, Mohsen Mirkhalaf

Abstract:
This repository contains the Jupyter code implementations of micromechanical and mesoscale neural networks for the multiscale analysis of elastic woven composites. Additionally, it includes the necessary input data for the models and the trained models stored as h5 files.

Introduction:
The analysis of composite materials often involves computationally expensive and time-consuming procedures. To address this issue and enable efficient multiscale analysis of composites, we propose the integration of neural networks and multiscale modeling techniques. This approach allows us to bypass the need for costly lower-scale material modeling and accelerates coupled multiscale analyses.

Micromechanical Neural Networks:
In this work, we focus on replacing the time-consuming micromechanical finite element analysis of unidirectional composites. Our micromechanical neural networks capture the local material properties of yarns in woven fabric composites within a multiscale framework. By leveraging a fast multiscale data generation procedure, these neural networks provide a more efficient alternative for estimating the behavior of unidirectional composites.

Mesoscale Neural Networks:
In addition to the micromechanical models, we have developed a second set of neural networks to estimate the elastic engineering coefficients of a particular weave architecture. These models take into account a broad range of dry resin and fiber properties as well as yarn fiber volume fraction. By employing these mesoscale neural networks, we can accurately predict the elastic properties of woven composites.

Repository Contents:

Micromechanical Neural Network Code: Jupyter code implementation for the micromechanical neural networks.
Mesoscale Neural Network Code: Jupyter code implementation for the mesoscale neural networks.
Input Data: Dataset containing the required input data for the models.
Trained Models: Pre-trained models stored as h5 files for immediate use.
Usage:
To utilize the provided neural networks, follow the instructions outlined in the respective Jupyter code notebooks. Ensure that the input data is appropriately formatted and accessible to the code.

Conclusion:
This repository offers a generalized, neural network-based approach for efficiently analyzing elastic woven composites at multiple scales. By integrating neural networks into the analysis workflow, we achieve a balance between computational efficiency and accuracy. Researchers and practitioners can leverage these models to expedite the analysis process and gain insights into the behavior of woven composites.

Please refer to the accompanying paper for a detailed explanation of the methodology and results.

Citation:
If you use the code or models in this repository, please cite the corresponding paper:

@article{ghane2023multiscale,
  title={A multiscale deep learning model for elastic properties of woven composites},
  author={Ghane, E and Fagerstr{\"o}m, M and Mirkhalaf, SM},
  journal={International Journal of Solids and Structures},
  pages={112452},
  year={2023},
  publisher={Elsevier}
}

We hope this repository serves as a valuable resource for the multiscale analysis of elastic woven composites using neural networks. For any inquiries or issues, please contact [ehsan.ghane@physics.gu.se].
