# [WIP] AI Edge Benchmarking
Compare inference delays across various edge devices


## ImageNet Classification (W=224, BS=1, ms)

|                            | VGG16 | VGG19 | ResNet50 | MobileNet v2 | EfficientNet | Vision Transformer |
|----------------------------|-------|-------|----------|--------------|--------------|--------------------|
| Wasabi 2.0 (ours)          |       |       |          |              |              |                    |
| Nvidia Jetson Nano         |       |       |          |              |              |                    |
| Google Coral + RP4         |       |       |          |              |              |                    |
| Intel Neural Compute Stick |       |       |          |              |              |                    |
| Xilinx DPU                 |       |       |          |              |              |                    |
| TVM VTA                    |       |       |          |              |              |                    |
