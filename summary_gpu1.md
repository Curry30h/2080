SUMMARY
===
| model | input size | param mem | feat. mem | flops  |
|-------|------------|--------------|----------------|-------------|
| resnet-50 | 224 x 224 | 98 MB | 103 MB | 4 BFLOPs |
| resnet-152 | 224 x 224 | 230 MB | 219 MB | 11 BFLOPs |
| inception-v3 | 299 x 299 | 91 MB | 89 MB | 6 BFLOPs |
| vgg-vd-19 | 224 x 224 | 548 MB | 63 MB | 20 BFLOPs |
| alexnet | 227 x 227 | 233 MB | 3 MB | 1.5 BFLOPs |
| ssd-300 | 300 x 300 | 100 MB | 116 MB | 31 GFLOPS |


**syn-replicated-fp32-1gpus**

Config | 6136-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |294.51 |
resnet152 |110.94 |
inception3 |191.41 |
inception4 |79.70 |
vgg16 |173.67 |
alexnet |3577.59 |
ssd300 |150.16 |


**syn-parameter_server-fp32-1gpus**

Config | 6136-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |292.33 |
resnet152 |110.78 |
inception3 |191.31 |
inception4 |79.61 |
vgg16 |173.19 |
alexnet |3550.93 |
ssd300 |150.15 |


**syn-replicated-fp16-1gpus**

Config | 6136-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |425.53 |
resnet152 |148.25 |
inception3 |241.59 |
inception4 |89.23 |
vgg16 |203.05 |
alexnet |4104.71 |
ssd300 |174.73 |


**syn-parameter_server-fp16-1gpus**

Config | 6136-GeForce_RTX_2080_Ti |
:------:|:------:|
resnet50 |427.87 |
resnet152 |150.39 |
inception3 |242.55 |
inception4 |89.91 |
vgg16 |205.98 |
alexnet |4165.15 |
ssd300 |175.74 |
