<h2 align="center">神奇的Prompt工程 🧙‍♂️</h2>

<p align="center">
  <img width="650" src="https://raw.githubusercontent.com/promptslab/Awesome-Prompt-Engineering/main/_source/prompt.png">
</p>

<p align="center">
  <p align="center">该存储库包含一个手动筛选的Prompt工程资源，重点关注于生成式预训练变压器（GPT）、ChatGPT、PaLM等。

</p>
 <h4 align="center">
  
  ```
     Prompt工程课即将来临...
  ```
  
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome" />
  </a>
  <a href="https://github.com/promptslab/Awesome-Prompt-Engineering/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="该存储库采用Apache 2.0许可发布" />
  </a>
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="http://makeapullrequest.com" />
  </a>
  <a href="https://discord.gg/m88xfYMbK6">
    <img src="https://img.shields.io/badge/Discord-Community-orange" alt="Community" />
  </a>
  <a href="https://colab.research.google.com/drive/1f4YG9stX9aHmsmh6ZhzjekJU4X4BIynO?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="colab" />
  </a>
</h4>


# 目录

- [论文](#论文)
- [工具和代码](#工具--代码)
- [API](#api)
- [数据集](#数据集)
- [模型](#模型)
- [AI内容检测器](#ai内容检测器)
- [教育](#教育)
  - [教程](#教程)
- [视频](#视频)
- [图书](#图书)
- [社群](#社群)
- [如何贡献](#如何贡献)


## 论文
📄
- **Prompt工程技术**：
  - [使用Prompt Pattern目录增强ChatGPT Prompt工程的方法](https://arxiv.org/abs/2302.11382) [2023] (Arxiv)
  - [基于梯度的离散优化用于Prompt微调和发现](https://arxiv.org/abs/2302.03668) [2023] (Arxiv)。- [综合提示：为大型语言模型生成思维链演示](https://arxiv.org/abs/2302.00618) [2023]（Arxiv）
  - [渐进提示：语言模型的连续学习](https://arxiv.org/abs/2301.12314) [2023]（Arxiv）
  - [批处理提示：带有LLM API的高效推断](https://arxiv.org/abs/2301.08721) [2023]（Arxiv）
  - [连续提示以解决复杂问题](https://arxiv.org/abs/2212.04092) [2022]（Arxiv）
  - [结构提示：将上下文学习扩展到1,000个示例](https://arxiv.org/abs/2212.06713) [2022]（Arxiv）
  - [大型语言模型是人类水平的提示工程师](https://arxiv.org/abs/2211.01910) [2022]（Arxiv）
  - [问我任何事：提示语言模型的简单策略](https://paperswithcode.com/paper/ask-me-anything-a-simple-strategy-for) [2022]（Arxiv）
  - [提示GPT-3要可靠](https://arxiv.org/abs/2210.09150) [2022]（Arxiv）
  - [分解提示：解决复杂任务的模块化方法](https://arxiv.org/abs/2210.02406) [2022]（Arxiv）
  - [PromptChainer：通过视觉编程链接大型语言模型提示](https://arxiv.org/abs/2203.06566) [2022]（Arxiv）
  - [调查扩散模型中的提示工程](https://arxiv.org/abs/2211.15462) [2022]（Arxiv）
  - [展示您的工作：使用语言模型进行中间计算的草稿本](https://arxiv.org/abs/2112.00114) [2021]（Arxiv）
  - [重新构思GPTk的教学提示](https://arxiv.org/abs/2109.07830) [2021]（Arxiv）
  - [奇妙有序的提示及其发现：克服小样本提示顺序敏感性](https://arxiv.org/abs/2104.08786) [2021]（Arxiv）
  - [规模的力量用于参数高效提示调整](https://arxiv.org/abs/2104.08691) [2021]（Arxiv）
  - [为大型语言模型编程：超越小样本范例](https://arxiv.org/abs/2102.07350) [2021]（Arxiv）- [Prefix-Tuning: 优化连续提示以进行生成](https://arxiv.org/abs/2101.00190) [2021] (Arxiv)

- **推理和上下文学习**：

  - [语言模型中的多模态思维链推理](https://arxiv.org/abs/2302.00923) [2023] (Arxiv)
  - [转念一想，我们不走单步思考的路！零-shot推理中的偏见和有害性](https://arxiv.org/abs/2212.08061) [2022] (Arxiv)
  - [ReAct：语言模型中推理和行动的协同作用](https://arxiv.org/abs/2210.03629) [2022] (Arxiv)
  - [语言模型是贪婪的推理者：对思维链的系统形式分析](https://arxiv.org/abs/2210.01240v3) [2022] (Arxiv)
  - [关于使语言模型变得更好的推理的进展](https://arxiv.org/abs/2206.02336) [2022] (Arxiv)
  - [大型语言模型是零-shot推理者](https://arxiv.org/abs/2205.11916) [2022] (Arxiv)
  - [像程序执行器一样推理](https://arxiv.org/abs/2201.11473) [2022] (Arxiv)
  - [自洽性提高了语言模型中的思维链推理](https://arxiv.org/abs/2203.11171) [2022] (Arxiv)
  - [重新思考演示的作用：什么使上下文学习起作用？](https://arxiv.org/abs/2202.12837) [2022] (Arxiv)
  - [学会解释：通过思维链进行科学问答的多模态推理](https://arxiv.org/abs/2209.09513v2) [2022] (Arxiv)
  - [Thought Chain提示在大型语言模型中引发推理](https://arxiv.org/abs/2201.11903) [2021] (Arxiv)
  - [针对常识推理的生成知识提示](https://arxiv.org/abs/2110.08387) [2021] (Arxiv)
  - [BERTese：学会与BERT交流](https://aclanthology.org/2021.eacl-main.316) [2021] (Acl)
  
- **评估和改进语言模型**：

  - [大型语言模型容易被无关上下文干扰](https://arxiv.org/abs/2302.00093) [2023] (Arxiv)
  - [爬取语言模型的内部知识库](https://arxiv.org/abs/2301.12810) [2023] (Arxiv)- **发掘语言模型行为的方法：模型编写的评估** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2212.09251)
  - **使用前校准：提高语言模型的少样本性能** [2021] (Arxiv) [原文链接](https://arxiv.org/abs/2102.09690)


- **语言模型的应用**：

  - **多模态恶意模因分类的提示** [2023] (Arxiv) [原文链接](https://arxiv.org/abs/2302.04156)
  - **用于社交对话合成的提示语言模型** [2023] (Arxiv) [原文链接](https://arxiv.org/abs/2302.03269)
  - **针对可控移情对话生成的常识感知提示** [2023] (Arxiv) [原文链接](https://arxiv.org/abs/2302.01441)
  - **程序辅助语言模型** [2023] (Arxiv) [原文链接](https://arxiv.org/abs/2211.10435)
  - **用于多语言法律判断预测的法律提示编写** [2023] (Arxiv) [原文链接](https://arxiv.org/abs/2212.02199)
  - **使用自然语言解决CS1问题的提示工程探究** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2210.15157)
  - **使用预训练语言模型进行情节创作** [2022] (Acl) [原文链接](https://aclanthology.org/2022.inlg-main.5)
  - **AutoPrompt：使用自动生成的提示语从语言模型中引出知识** [2020] (Arxiv) [原文链接](https://arxiv.org/abs/2010.15980)


- **威胁检测和对抗示例**:

  - **宪法人工智能：通过AI反馈无害** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2212.08073)
  - **忽略前一个提示：语言模型的攻击技术** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2211.09527)
  - **机器生成文本：威胁模型和检测方法全面调查** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2210.07321)
  - **通过手工制作的对抗示例评估预训练语言模型的易感性** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2209.02128)
  - **使用生成提示的毒性检测** [2022] (Arxiv) [原文链接](https://arxiv.org/abs/2205.12390)。- [我们如何知道语言模型所知道的？](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00324/96460/How-Can-We-Know-What-Language-Models-Know) [2020] (Mit) 


- **少样本学习和性能优化**：

  - [Promptagator：从8个示例进行少样本密集检索](https://arxiv.org/abs/2209.11755) [2022] (Arxiv) 
  - [Few-Shot提示进行文本推理的解释不可靠性](https://arxiv.org/abs/2205.03401) [2022] (Arxiv) 
  - [使预训练语言模型成为更好的少样本学习器](https://aclanthology.org/2021.acl-long.295) [2021] (Acl) 
  - [语言模型是少样本学习器](https://arxiv.org/abs/2005.14165) [2020] (Arxiv) 


- **文本到图像生成**：

  - [一种用于文本到图像生成的提示修饰符分类](https://arxiv.org/abs/2204.13988) [2022] (Arxiv) 
  - [Prompt工程文本到图像生成模型的设计指南](https://arxiv.org/abs/2109.06977) [2021] (Arxiv)
  - [使用潜在扩散模型进行高分辨率图像合成](https://arxiv.org/abs/2112.10752) [2021] (Arxiv)
  - [DALL·E：从文本中创建图像](https://arxiv.org/abs/2102.12092) [2021] (Arxiv)


- **文本到音乐/声音生成**：

  - [MusicLM：从文本生成音乐](https://arxiv.org/abs/2301.11325) [2023] (Arxiv) 
  - [ERNIE-Music：使用扩散模型进行文本到波形音乐生成](https://arxiv.org/pdf/2302.04456) [2023] (Arxiv)
  - [Noise2Music：使用扩散模型进行文本调制音乐生成](https://arxiv.org/abs/2301.11325) [2023) (Arxiv)
  - [AudioLM：一种基于语言建模的音频生成方法](https://arxiv.org/pdf/2209.03143) [2023] (Arxiv)
  - [Make-An-Audio：使用增强提示扩散模型进行文本到音频生成](https://arxiv.org/pdf/2301.12661.pdf) [2023] (Arxiv)


- **文本到视频生成**：

  - [Dreamix：视频扩散模型是通用视频编辑器](https://arxiv.org/pdf/2302.01329.pdf) [2023] (Arxiv)。- [调整视频：一次性调整图像扩散模型用于文本到视频生成](https://arxiv.org/pdf/2212.11565.pdf) [2022] (Arxiv)
  - [噪声到音乐：基于扩散模型的文本条件音乐生成](https://arxiv.org/abs/2301.11325) [2023] (Arxiv)
  - [音频LM：一种语言模型生成音频的方法](https://arxiv.org/pdf/2209.03143) [2023] (Arxiv)
  
  
- **概述**：

  - [Piloting Copilot and Codex: Hot Temperature, Cold Prompts, or Black Magic?](https://arxiv.org/abs/2210.14699) [2022] (Arxiv) 
  
  


## 工具和代码
🔧

|      名称              | 描述  | 链接 |
| :-------------------- | :----------: | :----------: |
| **GPT Index** | GPT Index 是一个由一组数据结构组成的项目，旨在使使用大型外部知识库与 LLM 更轻松。 | [[Github]](https://github.com/jerryjliu/gpt_index) |
| **WFGY 16 Problem Map** | 一个针对 LLM 流水线的供应商中立故障排查地图，重点关注 RAG、向量存储和长上下文提示。定义了 16 种具体的故障模式，并提供症状说明和最小化修复策略。 | [[Github]](https://github.com/onestardao/WFGY/tree/main/ProblemMap/README.md) |
| **Promptify** | 使用 LLM 解决 NLP 问题，使用 Promptify 轻松为 GPT、PaLM 等流行生成模型生成不同的 NLP 任务提示 | [[Github]](https://github.com/promptslab/Promptify) |
| **Better Prompt** | 在将 LLM 提示推送到生产之前测试测试套件 | [[Github]](https://github.com/krrishdholakia/betterprompt) |
| **Interactive Composition Explorerx** | ICE 是一个 Python 库和语言模型程序的跟踪可视化器。 | [[Github]](https://github.com/oughtinc/ice) |
| **LangChainx** | 通过组合使用 LLM 构建应用程序 | [[Github]](https://github.com/hwchase17/langchain) |
| **OpenPrompt** | 一个用于 Prompt 学习的开源框架 | [[Github]](https://github.com/thunlp/OpenPrompt) |
| **Prompt Engine** | 此存储库包含用于创建和维护大语言模型 (LLMs) Prompt 的 NPM 实用程序库。 | [[Github]](https://github.com/microsoft/prompt-engine) |"| **PromptInject** | PromptInject 是一个以模块化方式组装提示的框架，用于提供有关 LLM 对抗提示攻击鲁棒性的定量分析。 | [[Github]](https://github.com/agencyenterprise/PromptInject) |
| **Prompts AI** | GPT-3 的高级工作场所 | [[Github]](https://github.com/sevazhidkov/prompts-ai) |
| **Prompt Source** | PromptSource 是一个用于创建、共享和使用自然语言提示的工具包。 | [[Github]](https://github.com/bigscience-workshop/promptsource) |
| **ThoughtSource** | 一个用于机器思考科学的框架 | [[Github]](https://github.com/OpenBioLink/ThoughtSource) |


## Api
💻

|      名称                | 描述  | URL | 付费或开源 |
| :-------------------- | :----------: | :----------: | :----------: |
| **OpenAI** | 用于自然语言任务的 GPT-n，用于将自然语言翻译成代码的 Codex，以及用于创建和编辑原始图像的 DALL·E。 | [[OpenAI]](https://openai.com/api/) | 付费 |
| **CohereAI** | Cohere 通过一个 API 提供对先进的大型语言模型和自然语言处理工具的访问。 | [[CohereAI]](https://cohere.ai/) | 付费 |
| **Anthropic** | 即将推出 | [[Anthropic]](https://www.anthropic.com/) | 付费 |
| **FLAN-T5 XXL** | 即将推出 | [[HugginFace]](https://huggingface.co/docs/api-inference/index) | 开源 |



## 数据集
💾

|      名称                | 描述  | URL |
| :-------------------- | :----------: | :----------: |
| **P3 (Public Pool of Prompts)** | P3 (Public Pool of Prompts) 是一个包含各种 NLP 任务的 prompted English 数据集集合。 | [[HuggingFace]](https://huggingface.co/datasets/bigscience/P3) |
| **Awesome ChatGPT Prompts** | 该仓库包括用于更好地使用 ChatGPT 的 ChatGPT prompt curation。 | [[Github]](https://github.com/f/awesome-chatgpt-prompts) |"## 模型

🧠

|      名称                | 描述  | 链接 | 
| :-------------------- | :----------: | :----------: |
| **ChatGPT** | ChatGPT  | [[OpenAI]](https://chat.openai.com/) |
| **Codex** | Codex 模型是我们的 GPT-3 模型的后代，可以理解和生成代码。其训练数据包含自然语言和 GitHub 上数十亿行公共代码 | [[Github]](https://platform.openai.com/docs/models/codex) |
| **Bloom** | BigScience 大型开放科学开放获取多语言语言模型  | [[HuggingFace]](https://huggingface.co/bigscience/bloom) |
| **Facebook LLM** | OPT-175B 是 Meta 训练的 GPT-3 等效模型。它是目前可用的最大的预训练语言模型，具有 1750 亿个参数 | [[Alpa]](https://opt.alpa.ai/) |
| **GPT-NeoX** | GPT-NeoX-20B，一个经过训练的 200 亿个参数的自回归语言模型 | [[HuggingFace]](https://huggingface.co/docs/transformers/model_doc/gpt_neox) |
| **FLAN-T5 XXL** | Flan-T5 是一种指令调整模型，这意味着当作为提示的一部分给出指令时，它会表现出零射击行为。  | [[HuggingFace/Google]](https://huggingface.co/google/flan-t5-xxl) |
| **XLM-RoBERTa-XL** | XLM-RoBERTa-XL 模型在 2.5TB 的经过过滤的 CommonCrawl 数据上进行了预训练，其中包含 100 种语言 | [[HuggingFace]](https://huggingface.co/facebook/xlm-roberta-xxl) |
| **GPT-J** | 它是在 Pile 数据集上训练的类似于 GPT-2 的因果语言模型 | [[HuggingFace]](https://huggingface.co/docs/transformers/model_doc/gptj) |

| **写作提示** | 包含从在线论坛（reddit）抓取的 300K 个人编写的故事与写作提示的大型数据集 | [[Kaggle]](https://www.kaggle.com/datasets/ratthachat/writing-prompts) |
| **Midjourney 提示** | 从 MidJourney 的公共 Discord 服务器中抓取的文本提示和图像 URL | [[HuggingFace]](https://huggingface.co/datasets/succinctly/midjourney-prompts) || **PaLM-rlhf-pytorch** | RLHF（通过人类反馈的强化学习）在PaLM架构中的实现。基本上是ChatGPT，但加上了PaLM | [[Github]](https://github.com/lucidrains/PaLM-rlhf-pytorch) |
| **GPT-Neo** | 使用网格张量库实现模型并行的GPT-2和类GPT-3模型的实现。| [[Github]](https://github.com/EleutherAI/gpt-neo) |
| **LaMDA-rlhf-pytorch** | Google的LaMDA的开源预训练实现，使用PyTorch。添加类似于ChatGPT的RLHF。 | [[Github]](https://github.com/conceptofmind/LaMDA-rlhf-pytorch) |
| **RLHF** | 通过人的反馈实现强化学习的实现 | [[Github]](https://github.com/xrsrke/instructGOOSE) |
| **GLM-130B** | GLM-130B：一个开放的双语预训练模型| [[Github]](https://github.com/THUDM/GLM-130B) |

## AI内容检测器
🔎

| 名称 | 描述 | URL |
| :---:|:----:|:----:|
| **AI文本分类器** | AI文本分类器是一个经过精细调整的GPT模型，可以预测一段文本是来自于各种来源（如ChatGPT）的AI生成的可能性。 | [[OpenAI]](https://platform.openai.com/ai-text-classifier) |
| **GPT-2输出检测器** | 这是一个基于🤗/Transformers实现的RoBERTa的在线演示| [[HuggingFace]](https://huggingface.co/spaces/openai/openai-detector) |
| **Openai检测器** | 用于指示由AI编写的文本的AI分类器（OpenAI Detector Python wrapper）| [[GitHub]](https://github.com/promptslab/openai-detector) |

## 教程
📚

  - **Prompt工程简介**

    - [Prompt工程101-介绍和资源](https://www.linkedin.com/pulse/prompt-engineering-101-introduction-resources-amatriain)
    - [Prompt工程101](https://humanloop.com/blog/prompt-engineering-101)".- [SudalaiRajkumar 的 Prompt 工程指南](https://github.com/SudalaiRajkumar/Talks_Webinars/blob/master/Slides/PromptEngineering_20230208.pdf)

  - **生成式语言模型入门指南**

    - [生成式语言模型的初学者友好指南 - LaMBDA 指南](https://aitestkitchen.withgoogle.com/how-lamda-works)
    - [基于 Cohere 的生成式人工智能：第一部分 - 模型提示](https://txt.cohere.ai/generative-ai-part-1)

  - **Prompt 工程的最佳实践**

    - [OpenAI API Prompt 工程的最佳实践](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
    - [如何编写好的提示](https://andymatuschak.org/prompts)

  - **完整的 Prompt 工程指南**

    - [大型语言模型 Prompt 工程完整介绍](https://www.mihaileric.com/posts/a-complete-introduction-to-prompt-engineering)
    - [Prompt 工程指南：如何设计最佳提示](https://richardbatt.co.uk/prompt-engineering-guide-how-to-engineer-the-perfect-prompts)

  - **Prompt 工程的技术方面**

    - [GPT-3 Prompt 工程的 3 大原则](https://www.linkedin.com/pulse/3-principles-prompt-engineering-gpt-3-ben-whately)
    - [ChatGPT Prompt 工程的通用框架](https://medium.com/@thorbjoern.heise/a-generic-framework-for-chatgpt-prompt-engineering-7097f6513a0b)
    - [Prompt 编程方法](https://generative.ink/posts/methods-of-prompt-programming)

  - **Prompt 工程的资源**

    - [Awesome ChatGPT 提示](https://github.com/f/awesome-chatgpt-prompts)
    - [最佳 100+ 稳定扩散 Prompt](https://mpost.io/best-100-stable-diffusion-prompts-the-most-beautiful-ai-text-to-image-prompts)
    - [DALLE Prompt 书籍](https://dallery.gallery/the-dalle-2-prompt-book)
    - [OpenAI 烹饪书](https://github.com/openai/openai-cookbook)
    - [Microsoft 的 Prompt 工程](https://microsoft.github.io/prompt-engineering)

## 视频
🎥- [进阶版ChatGPT Prompt工程](https://www.youtube.com/watch?v=bBiTR_1sEmI)
- [ChatGPT：面向初学者的5个Prompt工程秘诀](https://www.youtube.com/watch?v=2zg3V66-Fzs)
- [CMU高级自然语言处理2022：Prompting](https://youtube.com/watch?v=5ef83Wljm-M&feature=shares)
- [Prompt工程-一个新的职业？](https://www.youtube.com/watch?v=w102J3_9Bcs&ab_channel=PatrickDebois)
- [ChatGPT指南：使用更好的Prompt让你的结果提升10倍](https://www.youtube.com/watch?v=os-JX1ZQwIA)
- [语言模型和Prompt工程：NLP中Prompting方法的系统调查](https://youtube.com/watch?v=OsbUfL8w-mo&feature=shares)
- [Prompt工程101：自动完成、零样本、单样本和少样本提示](https://youtube.com/watch?v=v2gD8BHOaX4&feature=shares)


## 社区
🤝

- [OpenAI Discord](https://discord.com/invite/openai)
- [PromptsLab Discord](https://discord.gg/m88xfYMbK6)
- [学习Prompting](https://discord.gg/7enStJXQzD)
- [r/ChatGPT Discord](https://discord.com/invite/r-chatgpt-1050422060352024636)
- [MidJourney Discord](https://discord.com/invite/MidJourney)



# 如何贡献

我们欢迎贡献这个列表！实际上，这也是我创建它的主要原因——鼓励贡献和鼓励人们订阅更改以便及时了解大型语言模型(LLMs)和Prompt工程领域的新的、令人兴奋的发展动态。

在贡献之前，请花点时间查看我们的[贡献指南](contributing.md)。这些指南将有助于确保您的贡献与我们的目标一致，并符合我们的质量和相关性标准。感谢您有兴趣为这个项目做出贡献！


<h6 align="center">
<small><small>图片来源：docs.cohere.ai </small> </small>
</h6>