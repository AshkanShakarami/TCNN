# TCNN
TCNN: A Transformer Convolutional Neural Network for artifact classification in whole slide images

We have published the TCNN at [https://www.sciencedirect.com/science/article/pii/S1746809423002458]

In this repository, we have included the TCNN codebook for research purposes. Should you utilize any concepts from the model, we kindly request that you acknowledge our work by providing proper attribution through citations.

https://doi.org/10.1016/j.bspc.2023.104812 [Shakarami, A., Nicolè, L., Terreran, M., Dei Tos, A. P., & Ghidoni, S. (2023). Tcnn: A transformer convolutional neural network for artifact classification in whole slide images. Biomedical Signal Processing and Control, 84, 104812.]

![TCNN_Architecture](https://github.com/AshkanShakarami/TCNN/assets/101816571/918bdd8c-c72d-463d-ad6f-07f1085bfb4b)  -----------------------------------The proposed Transformer Convolutional Neural Network (TCNN) Architecture------------------------------------


What is the TCNN? The TCNN, or Transformer Convolutional Neural Network, introduced in this paper, aims to automate the detection of artifacts in pathological images. By treating artifact detection as a binary classification task, the TCNN offers a solution to identify these unwanted patterns that may arise during slide processing. This method alleviates the need for laboratory technicians to label manually, reducing the risk of erroneous data being sent for analysis by pathologists and physicians. Artifact patches, if not identified and excluded, can compromise the accuracy of Computer-Aided Diagnosis (CAD) systems.


![TCNN_Outputs](https://github.com/AshkanShakarami/TCNN/assets/101816571/859bcb1b-3190-48f7-924a-9c8922f4640b)
The pictorial objective form of this paper. a) A tailed whole slide image using QuPath software, b) the result of tailing, and c) Non-Artifact tiles (The clean dataset).

