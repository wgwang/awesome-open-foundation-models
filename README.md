# 开源开放基础大模型


旨在记录开源开发大模型发展情况，随时更新，欢迎在**Issues**中提供提供**线索**和**素材**

使用数据请注明来源：**微信公众号：走向未来** 和 **仓库：https://github.com/wgwang/awesome-open-foundation-models**


Awesome family related to LLMS includes:
- https://github.com/wgwang/awesome-LLM-benchmarks
- https://github.com/wgwang/awesome-LLMs-In-China
- https://github.com/wgwang/awesome-open-foundation-models


大模型相关的Awesome系列包括：
- 大模型评测数据集：
  https://github.com/wgwang/awesome-LLM-benchmarks
- 中国大模型列表：
  https://github.com/wgwang/awesome-LLMs-In-China
- 开源开放基础大模型列表：
  https://github.com/wgwang/awesome-open-foundation-models


微信扫码关注我的微信公众号：**走向未来**，分享有关大模型、AGI、知识图谱、深度学习、强化学习、计算机视觉、自然语言处理等等与人工智能有关的内容。

![](imgs/走向未来.jpg)  

**Star一下，举手之劳！**

## 开源开放的基础大模型列表


|序号|名称|参数规模|数据规模|说明|
|:-|:-|:-|:-|:-|
|1|[LLaMA-2](Open-LLMs/llama2.md)|7B,13B,34B,70B|2T|可商用|
|2|[Falcon](Open-LLMs/falcon.md)|7B,40B,180B|3.5T|数据集[ RefinedWeb](https://huggingface.co/datasets/tiiuae/falcon-refinedweb)|
|3|[baichuan-2](Open-LLMs/baichuan2.md)|7B,13B|2.6T|开放，商用需授权，[baichuan-1](Open-LLMs/baichuan.md)|
|4|[InternLM](Open-LLMs/internlm.md)|7B,20B|2.3T|开放，商用需授权|
|5|[BLOOM](Open-LLMs/bloom.md)|3B,7.1B,176B|366B|可商用，最为宽松，[详细介绍](https://mp.weixin.qq.com/s/ia-yrmXbnlooRA3K1hoTwQ)|
|6|GALACTICA|6.7B,30B,120B|106B|开放的科学文本和数据|
|7|[LLaMA](Open-LLMs/llama.md)|7B,13B,30B,65B|1.4T|Meta，代码开源，模型“泄露”,不可商用，[详细介绍](https://mp.weixin.qq.com/s/dKInMi6P80GXecUtR3WQsA)|
|8|MOSS-moon|16B|700B|6.67x1022 FLOPs|
|9|ChatGLM2|6B|1.4T||
|10|StableLM|3B,7B|800B||
|11|RedPajama-INCITE|3B,7B|1T||
|12|GPT-NeoX|20B|3.15M|800GB的[The Pile](https://arxiv.org/abs/2101.00027)数据集|
|13|OpenLLaMA|3B,7B,13B|1T||
|14|MPT|7B,30B|1T|
|15|Pythia|2.8B,6.9B,12B|300B||
|16|XGen|7B|1.5T||
|17|OPT|6.7B,13B,30B,66B,175B|180B||
|18|[Qwen](Open-LLMs/qwen.md)|7B,14B,72B|2.4T,3.0T,3.0T||
|19|XVERSE|13B,65B|1.4T,2.6T||
|20|[Aquila2](https://github.com/FlagAI-Open/Aquila2)|7B,34B|2T||
|21|Prithvi|||IBM+NASA,地理空间，100M（图片）|
|22|[Skywork](Open-LLMs/skywork.md)|13B|3.2T|昆仑万维·天工|
|23|[Deepseek Coder](https://github.com/deepseek-ai/DeepSeek-Coder)|1.3B,6.7B,33B|2T|Deepseek Coder comprises a series of code language models trained on both 87% code and 13% natural language in English and Chinese, with each model pre-trained on 2T tokens.|
|24|Aquila|7B||悟道·天鹰|
|25|Yi|6B,34B|3T||
|26|Mistral|7B||欧洲|
|27|Yuan-2|2B,51B,102B||源|
|28|Mistral 7BX8 MoE|56B||7BX8 MoE|
|29|BlueLM|7B|2.6T|https://github.com/vivo-ai-lab/BlueLM|
|30|YAYI 2|30B|2.65T|https://github.com/wenge-research/YAYI2|
|31|CodeShell|7B|0.5T|https://github.com/WisdomShell/codeshell|




## 非基础大模型
- WizardLM，WizardMath，WizardCoder
- Alpaca
- Vicuna
- Guanaco
- [CodeLLaMA](Open-LLMs/codellama.md)
  - 7B,13B,34B，基于LLaMA2，增加了650B左右的代码词元进行增量训练和微调



## 模型架构

- [GPTQ](https://github.com/IST-DASLab/gptq)
- [LLaMA](https://github.com/facebookresearch/llama)



# 微信公众号：走向未来

欢迎扫码关注微信公众：**走向未来**，公众号专注于分享AGI、大模型、知识图谱、深度学习、强化学习等技术、系统架构、应用场景和案例等内容。

![](imgs/the-land-of-future.jpeg)  


# 珠峰书

珠峰书《知识图谱：认知智能理论与实战》一书全面介绍了知识图谱的构建技术、存储技术和应用技术、Transformer、图神经网络等内容，欢迎购买。具体来说，包括：
- 知识图谱模式设计、知识抽取、图数据库、知识计算、知识推理、知识问答、知识推荐等全方面的内容
- 详细介绍了Transformer模型细节和实现方法，是大模型的基础技术
- 国内首本提到向量数据库的书籍
- 简要介绍了多模态知识融合的内容，书中以“月亮”为例，提出应当把图片的月亮、各种不同语言的文本月亮和和月亮的读音等，都应当融合到同一个知识点中。这正是多模态大模型所做的。
- 其他一些关于神经科学、脑科学和哲学中对智能的思考
  
![](imgs/kgbook.jpg)

