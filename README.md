# Brain Tumor Segmentation: 2.5D Attention U-Net vs 3D U-Net

PyTorch semester project on the BraTS 2020 dataset (4 MRI modalities, binary tumor mask), 100-patient cohort with patient-level train/validation split.

| Model | Dice |
|---|---|
| Attention U-Net (2D) | 0.843 |
| 2.5D Attention U-Net | 0.884 |
| 3D U-Net (96^3 tumor-centred patches, validation patients) | 0.716 |

Mixed precision (AMP), best-checkpoint selection and threshold tuning. The dataset is not included; download BraTS 2020 separately.
Deep Learning course, MS in AI at LUMS.
