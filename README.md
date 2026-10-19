# radius-models

Core ML models for **radius**, a local background remover for macOS.

| File | Source | Input | License |
|---|---|---|---|
| `BiRefNet_HR-matting.mlpackage.zip` | [ZhengPeng7/BiRefNet_HR-matting](https://huggingface.co/ZhengPeng7/BiRefNet_HR-matting) | RGB 1×3×2048×2048 in [0, 1] | MIT |

Converted with coremltools 9 (fp16, `torch.export`, real deformable convolution via grid-sample
decomposition, ImageNet normalisation and sigmoid baked in). Output: alpha matte 1×1×2048×2048 in [0, 1].

SHA-256 of the zip: `7cf712c7b00bd544880d31668a3d378f6972e5b01e7194d967e6250f9b920345`

BiRefNet: Zheng et al., "Bilateral Reference for High-Resolution Dichotomous Image Segmentation", CAAI AIR 2024.
