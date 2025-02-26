# DeepSeek_Training
DeepSeek finetune
DeepSeek R1 GPRO

准备
需要访问HF，下载模型和数据。

代理：
export https_proxy=192.168.100.111:8965
export http_proxy=192.168.100.111:8965
all_proxy=socks5://192.168.100.111:8964
HF镜像
export HF_ENDPOINT=https://hf-mirror.com

微调 LORA SFT 
显存占用
8510MiB / 24564MiB  利用率基本100%


报错
AttributeError: _unwrapped_old_generate
在训练前，将模型设置为训练模型FastLanguageModel.for_training(model)
