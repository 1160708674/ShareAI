# 1. 系统配置

系统：Ubuntu 20.04

 GPU: Driver Version: 515.65.01    CUDA Version: 11.7   NVIDIA A40  GPU

# 2. Python版本

Python 3.8.8 

# 3. requirements

matplotlib==3.3.4
numpy==1.20.1
pandas==1.2.4
torch==1.12.1+cu116
tqdm==4.59.0
transformers==4.21.1

# 4. 运行说明

运行以下脚本代码：

```bash
./train.sh
```

将开始模型训练，训练完成的模型保存在：

```
./results/adv_all_时间戳/
```

线上分数最高模型在ep_23_xxxx文件夹中，将

```
./results/adv_all_时间戳/ep_23_xxxx
```

文件夹内的文件，拷贝至

```
/model/pt_models
```

就能够实现线上推理了，当前/model/pt_models中存放了可复现最高分的模型。# 1. 系统配置

系统：Ubuntu 20.04

 GPU: Driver Version: 515.65.01    CUDA Version: 11.7   NVIDIA A40  GPU

# 2. Python版本

Python 3.8.8 

# 3. requirements

matplotlib==3.3.4
numpy==1.20.1
pandas==1.2.4
torch==1.12.1+cu116
tqdm==4.59.0
transformers==4.21.1

# 4. 运行说明

运行以下脚本代码：

```bash
./train.sh
```

将开始模型训练，训练完成的模型保存在：

```
./results/adv_all_时间戳/
```

线上分数最高模型在ep_23_xxxx文件夹中，将

```
./results/adv_all_时间戳/ep_23_xxxx
```

文件夹内的文件，拷贝至

```
/model/pt_models
```

就能够实现线上推理了，当前/model/pt_models中存放了可复现最高分的模型。
