# An-attention-based-deep-learning-method-for-continuous-interval-seismic-phase-picking

![SRL_f1](https://github.com/user-attachments/assets/38278b1f-4495-4935-afee-0b1da2e2e244)

We propose an enhanced seismic phase picking model based on an improved UNet architecture, integrating Convolutional Block Attention Module (CBAM), Parallel Attention, and Long Short-Term Memory (LSTM) units, along with a novel labeling strategy that captures continuous intervals from P-wave to S-wave arrivals for comprehensive seismic signal representation. Compared to the original PhaseNet model, our approach achieves significant improvements in precision and recall on the STEAD dataset, with a 4.6% increase in F1 score for S-wave picking under low signal-to-noise conditions, and demonstrates strong generalization capabilities across various seismic scenarios on the INSTANCE dataset. The model remains effective with missing waveform channels, offering a robust solution for global earthquake monitoring and interpretation.

#2025/10/21

The code for building the model has been uploaded to Model_code.ipynb.

The code for creating the dataset and labels has been uploaded to Dataset_and_label.ipynb.

