# model_seg_tem-multires

TEM axon/myelin segmentation, trained across multiple pixel sizes (TEM1 + TEM2) for resolution invariance. nnUNet 2.8.1, fold_all.

Weights are packaged as a release asset here and referenced from `model_cards.yaml` in the main [AxonDeepSeg](https://github.com/axondeepseg/axondeepseg) repo. Training code and eval lives in the ResInv_exp resolution invariance experiment.
