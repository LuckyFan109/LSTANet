# LSTANet
Long Short-Term Aggregation Network for Event-Based High-Speed Object Detection

![图片描述](图片链接)

The code is being organized and will be publicly available soon.

# Benchmark
| Methods | Representation | Gen1 mAP | Gen1 Runtime | 1 Mpx mAP | 1 Mpx Runtime | Params |
|---------|----------------|----------|--------------|-----------|---------------|--------|
| YOLOX-S ($\Delta t=50ms$) | Event temporal image | 38.1 | **3.3ms** | 39.3 | **3.3ms** | 8.9M |
| LSTANet-S($\Delta t_s=50ms$) | Event temporal image | 43.9 | 5.8ms | 43.0 | 5.8ms | 9.1M |
| LSTANet-M($\Delta t_s=50ms$) | Event temporal image | 47.7 | 7.1ms | 46.4 | 7.4ms | 25.7M |
| LSTANet-L($\Delta t_s=50ms$) | Event temporal image | 48.8 | 9.1ms | 48.3 | 10.3ms | 54.8M |
| LSTANet-X($\Delta t_s=50ms$) | Event temporal image | **49.3** | 12.4ms | **48.8** | 15.3ms | 100.0M |
<!---
| LSTANet-S($\Delta t_s=10ms$) | Event temporal image | 42.1 | 5.7ms | 42.6 | 5.7ms | 9.1M |
| LSTANet-X($\Delta t_s=10ms$) | Event temporal image | 48.0 | 12.4ms | - | - | 100.0M |
-->

# Abstract

# Datasets
## Gen1 Automotive Detection Dataset
The Gen1 dataset can be downloaded [here](https://www.prophesee.ai/2020/01/24/prophesee-gen1-automotive-detection-dataset/).
## 1Mpx Detection Dataset
The 1Mpx dataset can be downloaded [here](https://www.prophesee.ai/2020/11/24/automotive-megapixel-event-based-dataset/).
# References
Thanks to their great work
* [Megvii-BaseDetection/YOLOX](https://github.com/Megvii-BaseDetection/YOLOX)
* 
# License
This repo is released under the Apache 2.0 license. Please see the LICENSE file for more information.
