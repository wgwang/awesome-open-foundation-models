# 千问2

摘要：阿里云发布的千问大模型，发布于2024-05-23，涵盖5种模型规模，包括0.5B、1.5B、7B、57B-A14B(MoE模型）和72B，支持32K长度的上下文。同时，指令微调的模型外推到128K的上下文长度。没有明确训练设施和训练数据情况，仅说明使用了超过7T tokens的训练数据。

## 基础信息

- 由阿里云团队开发，中文领域超强的一个模型
- 多种参数规模的自回归语言模型：0.5B、1.5B、7B、57B-A14B(MoE模型）和72B
- 使用了超过7T的训练语料


## 资料集合

[代码仓库](https://github.com/QwenLM/Qwen2)
[modelscope仓库](https://modelscope.cn/organization/qwen) 和 [HuggingFace仓库](https://huggingface.co/collections/Qwen/qwen2-6659360b33528ced941e557f)



## 参数

|名称|Qwen2-72B|QWen2-7B|
|:-|:-|:-|
|隐变量维度dimension|8192|3584|
|自注意力头的个数n heads|64|28|
|GQA分组数量G|8|7|
|层数n layers|80|28|
|词表大小Vocab size|152000|152000|
|输入序列长度sequence length|32k|32k|
|数据规模词元数量n tokens|7T|7T|


## 训练模型的算力设施

无披露

## 模型下载

建议使用72B 的量化版本，推荐：
- [Qwen2-72B-Instruct-AWQ](https://modelscope.cn/models/qwen/Qwen2-72B-Instruct-AWQ)
- [Qwen2-72B-Instruct-GPTQ-Int4](https://modelscope.cn/models/qwen/Qwen2-72B-Instruct-GPTQ-Int4)

其他模型从下面仓库中下载：

[modelscope仓库](https://modelscope.cn/organization/qwen) 

[HuggingFace仓库](https://huggingface.co/collections/Qwen/qwen2-6659360b33528ced941e557f)



## 效果方面

中文要比 llama-3-70B 略强；其他语言弱了一些。



## 训练数据

无公开，据传闻为超过7T tokens

## 模型架构

未详细研究

  