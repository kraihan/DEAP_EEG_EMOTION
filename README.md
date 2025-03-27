Source code for "A comparative study of time–frequency features based spatio-temporal analysis with varying multiscale kernels for emotion recognition from EEG", Md Raihan Khan, Airin Akter Tania, Mohiuddin Ahmad.
Link: https://www.sciencedirect.com/science/article/pii/S1746809425003374
For any information, kindly email me: kraihan918@gmail.com
Dataset Source: The DEAP dataset can be downloaded from https://www.eecs.qmul.ac.uk/mmv/datasets/deap/download.html

Project Files Overview:

Figures.ipynb: Contains the code for generating significant figures used in the manuscript

Featurization.ipynb: Extracts four key EEG features: Differential Entropy (DE), Wavelet Energy (WE), Cross-Correlation (XCOR), and Phase Locking Value (PLV).

model-training.ipynb: Code for training the proposed model. You can modify the feature type and kernel size to achieve the desired output. The model can reach an accuracy of up to 98.97%.

DE-arousal-kernel-3.ipynb: An alternative implementation for training the model

cnn_classifier_wavelet_energy_arousal_full_3.pth: Trained model Weight.  Pretrained model weights. This model was trained on only 10% of the data, so its performance is not as high as the fully trained version but is provided for usability.   

Future Research Directions: 
If you're interested in further research or writing a paper in this field, consider the following:
 1. Filter Size Variation – Experiment with different convolution filter sizes and analyze their impact on accuracy.
 2. Model Complexity Optimization – Adjust the number of convolutional layers to explore accuracy dependencies while reducing model complexity.
 3. Learning Rate Optimization – Implement a variable or decaying learning rate to improve accuracy significantly.
 4. Modern Classifiers – Explore Transformer-based models for EEG emotion recognition.
 5. Attention Mechanisms – Use Smooth Grad-CAM, SHAP, Score-CAM, and Integrated Gradients to identify important EEG frames, then apply frame attention to reduce input complexity and enhance accuracy.
 6. Electrode Relationship Modeling – Implement 3D CNN + Spatial-Temporal Graph Convolution to capture electrode dependencies effectively.
 7. Feature Engineering – Evaluate performance using Discrete Wavelet Transform (DWT) with the ‘db4’ wavelet.
 8. Scale Variation Analysis – Modify exScale and totalScale parameters to assess their influence on accuracy.
 9. Connectivity-Based Features – Integrate different connectivity measures such as: Pearson Correlation,  Mutual Information, Transfer Entropy




If you find this helpful, kindly cite this.

@article{KHAN2025107826,
title = {A comparative study of time–frequency features based spatio-temporal analysis with varying multiscale kernels for emotion recognition from EEG},
journal = {Biomedical Signal Processing and Control},
volume = {107},
pages = {107826},
year = {2025},
issn = {1746-8094},
doi = {https://doi.org/10.1016/j.bspc.2025.107826},
url = {https://www.sciencedirect.com/science/article/pii/S1746809425003374},
author = {Md Raihan Khan, Airin Akter Tania,  Mohiuddin Ahmad},
}


@INPROCEEDINGS{10499496,
  author={Khan, Md Raihan and Ahmad, Mohiuddin},
  booktitle={2024 International Conference on Advances in Computing, Communication, Electrical, and Smart Systems (iCACCESS)}, 
  title={Mental Stress Detection from EEG Signals Using Comparative Analysis of Random Forest and Recurrent Neural Network}, 
  year={2024},
  pages={1-6},
  doi={https://doi.org/10.1109/iCACCESS61735.2024.10499496}}




