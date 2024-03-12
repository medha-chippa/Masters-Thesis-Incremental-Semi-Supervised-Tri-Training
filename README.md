# Masters-Thesis-Incremental-Semi-Supervised-Tri-Training

In this work, we present a novel and integrated framework, called Incremental Semi-Supervised Tri-Training, for incremental update as well as personalization of models residing on edge computing devices in the absence of domain specific labelled data. The proposed framework encompasses three heavy weight neural networks working collaboratively to generate high quality pseudo-labels in a selfsupervised manner to train a teacher model. The knowledge from the teacher model is then distilled into the student model residing on the edge device. The developed models are incrementally updated resulting in personalization of the edge model over time without requiring labels/annotations. We demonstrate the efficacy of the proposed framework in the context of a sleep staging application using the Physionet Sleep EDF-Expanded data repository.

The following are the major contributions of our work and the key 
features of the system proposed: 
• An approach called Incremental Semi-Supervised TriTraining for the purpose of carrying out model personalization in the absence of domain specific labeled data 
• A lighter version of a heavy DL framework capable of being deployed in a real-time inference setting and performing comparably well. 
• A framework supported by transfer-learning to shield the model from being susceptible to retraining or large training times. 
• Develop a model that doesn’t rely on domain specific labeled data to achieve personalization/domain adaptation. 
