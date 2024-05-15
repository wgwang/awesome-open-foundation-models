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

- 国内开源大模型两大霸主
  - Qwen 
  - DeepSeeker
  - 两个都在杭州，杭州上大分！
- 国外开源大模型两大霸主
  - LLaMA 美国
  - Mistral 欧洲



|序号|名称|参数规模|数据规模|发布时间|说明|
|:-|:-|:-|:-|:-|:-|
|1|[LLaMA-2](Open-LLMs/llama2.md)|7B,13B,34B,70B|2T|2023-07-18|可商用|
|2|[Falcon](Open-LLMs/falcon.md)|7B,40B,180B|3.5T|2023-09-06|数据集[ RefinedWeb](https://huggingface.co/datasets/tiiuae/falcon-refinedweb)|
|3|[baichuan-2](Open-LLMs/baichuan2.md)|7B,13B|2.6T|2023-09-06|[baichuan-1](Open-LLMs/baichuan.md)|
|4|[InternLM](Open-LLMs/internlm.md)|7B,20B|2.3T||开放，商用需授权|
|5|[BLOOM](Open-LLMs/bloom.md)|3B,7.1B,176B|366B||[详细介绍](https://mp.weixin.qq.com/s/ia-yrmXbnlooRA3K1hoTwQ)|
|6|GALACTICA|6.7B,30B,120B|106B||开放的科学文本和数据|
|7|[LLaMA](Open-LLMs/llama.md)|7B,13B,30B,65B|1.4T||[详细介绍](https://mp.weixin.qq.com/s/dKInMi6P80GXecUtR3WQsA)|
|8|MOSS-moon|16B|700B||6.67x1022 FLOPs|
|9|[ChatGLM3](https://github.com/THUDM/ChatGLM3)|6B|1.4T|2023-10-25|
|10|StableLM|3B,7B|800B||
|11|RedPajama-INCITE|3B,7B|1T|||
|12|GPT-NeoX|20B|3.15M||800GB的[The Pile](https://arxiv.org/abs/2101.00027)数据集|
|13|OpenLLaMA|3B,7B,13B|1T|||
|14|MPT|7B,30B|1T||
|15|Pythia|2.8B,6.9B,12B|300B|||
|16|XGen|7B|1.5T|||
|17|OPT|6.7B,13B,30B,66B,175B|180B|||
|18|[Qwen](Open-LLMs/qwen.md)|7B,14B,72B|2.4T,3.0T,3.0T|||
|19|XVERSE|13B,65B|1.4T,2.6T|||
|20|[Aquila2](https://github.com/FlagAI-Open/Aquila2)|7B,34B|2T|||
|21|Prithvi||||IBM+NASA,地理空间，100M（图片）|
|22|[Skywork](Open-LLMs/skywork.md)|13B|3.2T|2023-10-22|昆仑万维·天工|
|23|[Deepseek Coder](https://github.com/deepseek-ai/DeepSeek-Coder)|1.3B,6.7B,33B|2T||87% code and 13% 中英文文本|
|24|Aquila|7B||2023-06-08|悟道·天鹰|
|25|Yi|6B,34B|3T|2023-11-04|零一万物|
|26|Mistral|7B|||欧洲|
|27|Yuan-2|2B,51B,102B|288B|2023-12-21|源|
|28|Mistral MoE|46.7B||2023-12-11|7BX8 MoE,12.9B/46.7B|
|29|BlueLM|7B|2.6T|2023-10-16|https://github.com/vivo-ai-lab/BlueLM|
|30|YAYI 2|30B|2.65T|2023-12-15|https://github.com/wenge-research/YAYI2|
|31|CodeShell|7B|0.5T|2023-09-22|https://github.com/WisdomShell/codeshell|
|32|[DeepSeek-V2](https://github.com/deepseek-ai/DeepSeek-V2)|236B|8.1T|2024-05-06|MoE 21B/236B，160Experts，2Activate|
|33|[LLaMA-3](https://ai.meta.com/blog/meta-llama-3/)| 8B,70B |15T| 2024-04-18||
|34|[QWen-1.5](https://github.com/QwenLM/Qwen1.5)|0.5B,1.8B,4B,7B,14B,32B,72B|2.4T,2.4T,2.4T,4T,4T,3T,3T|2024-02-06||
|35|[QWen-1.5-110B](https://github.com/QwenLM/Qwen1.5)|110B|2.2T|2024-04-24||
|36|[DBRX](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm)|132B|12T|2024-03-27|MOE 36B/132B, 4/16experts|
|37|[Gemma](https://huggingface.co/blog/gemma)|7B,2B|6T|2024-02-20|终端设备|
|38|[Yi-1.5](https://github.com/01-ai/Yi-1.5)|6B,9B,34B|3.5T|2024-05-13|零一万物，在Yi之上用了500B 语料增量训练得到|
|39|Yi-VL|6B,34B||2024-01-18|Clip ViT-H/14+Yi-6/34B-Chat,100M图文对|
|40|[Hunyuan-DiT](https://github.com/Tencent/HunyuanDiT)|1.5B||2024-05-13|腾讯混元文生图|
|41|[Command-R]()|35B,104B|1.5T|2024-04-03|Focus RAG|
|42|Mistral 8X22B|141B||2024-4-17|8X22B MOE, 39B/141B|
|43|[Arctic](https://github.com/Snowflake-Labs/snowflake-arctic)|480B|3.5T|2024-04-22|Dense(10B)-MoE(128X3.66B), 17B/480B，3阶段训练，1T+1.5T+1T tokens|
|44|[Grok-1](https://github.com/xai-org/grok-1)|314B||2024-03-17|MoE 8 Expert| 
|45|[InternLM2](https://github.com/InternLM/InternLM)|7B,20B|2.3T|2023-09-18|
|46|[stableLM-2]|12B|2T|2024-03-21||






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

