# multi_gpu_training_bert4torch
基于bert4torch框架，单机多卡的pytorch简洁实现 (DP, DDP)

1. 本脚本全部基于[bert4torch](https://github.com/Tongjilibo/bert4torch)框架，主要是用pytorch复现[bert4keras](https://github.com/bojone/bert4keras)以及各种实例
2. 如果链接打不开，可能是因为源文件更新，可直接访问[bert4torch_example](https://github.com/Tongjilibo/bert4torch/tree/master/examples)
3. 欢迎 star [bert4torch](https://github.com/Tongjilibo/bert4torch)源项目

---
- [task_data_parallel.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/training_trick/task_data_parallel.py)：任务例子，DataParallel模式的多GPU训练方式
- [task_distributed_data_parallel.py](https://github.com/Tongjilibo/bert4torch/blob/master/examples/training_trick/task_distributed_data_parallel.py)：任务例子，DistributedDataParallel模式的多GPU训练方式
