# TCNN
TCNN: A Transformer Convolutional Neural Network for artifact classification in whole slide images [https://www.sciencedirect.com/science/article/pii/S1746809423002458]

The TCNN, or Transformer Convolutional Neural Network, automates artifact detection in pathological images. It addresses artifact detection as a binary classification task, identifying unwanted patterns that may arise during slide processing. This method reduces laboratory technicians' need for manual labeling, minimizing the risk of sending erroneous data for analysis. Failure to identify and exclude artifact patches can jeopardize the accuracy of Computer-Aided Diagnosis (CAD) systems.

We have included the TCNN codebook in this repository for research purposes. Should you utilize any concepts from the model, we kindly request that you acknowledge our work by providing proper attribution through citations [Shakarami, A., Nicolè, L., Terreran, M., Dei Tos, A. P., & Ghidoni, S. (2023). Tcnn: A transformer convolutional neural network for artifact classification in whole slide images. Biomedical Signal Processing and Control, 84, 104812.]; https://doi.org/10.1016/j.bspc.2023.104812

For inquiries, please feel free to contact Dr. Ashkan Shakarami (ashkan.shakarami@phd.unipd.it, ashkan.shakarami.ai@gmail.com) or any other authors listed in the paper.

![TCNN_Architecture](https://github.com/AshkanShakarami/TCNN/assets/101816571/918bdd8c-c72d-463d-ad6f-07f1085bfb4b)  ----------------The proposed Transformer Convolutional Neural Network (TCNN) Architecture----------------

![TCNN_Outputs](https://github.com/AshkanShakarami/TCNN/assets/101816571/859bcb1b-3190-48f7-924a-9c8922f4640b)
------------The pictorial objective form of this paper. a) A tailed whole slide image using QuPath software, b) the result of tailing, and c) Non-Artifact tiles (The clean dataset).------------

The required libraries have been mentioned in the TCNN_Codes.ipynb file. For the Python library, We used Python version 3.9.

