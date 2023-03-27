<h2 align="center">神奇的提示工程 🧙‍♂️ </h2>

<p align="center">
  <img width="650" src="https://raw.githubusercontent.com/promptslab/Awesome-Prompt-Engineering/main/_source/prompt.png">
</p>

<p align="center">
  <p align="center">这个仓库收集了手动策划资源，侧重于生成式预训练变压器（GPT）、ChatGPT、PaLM等提示工程
  
</p>
 <h4 align="center">
  
  ```
     提示工程课程即将上线..
  ```
  
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome" />
  </a>
  <a href="https://github.com/promptslab/Awesome-Prompt-Engineering/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg" alt="Awesome-Prompt-Engineering由 Apache 2.0 许可发布。" />
  </a>
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="http://makeapullrequest.com" />
  </a>
  <a href="https://discord.gg/m88xfYMbK6">
    <img src="https://img.shields.io/badge/Discord-社区-orange" alt="Community" />
  </a>
  <a href="https://colab.research.google.com/drive/1f4YG9stX9aHmsmh6ZhzjekJU4X4BIynO?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="colab" />
  </a>
</h4>


# 目录

- [论文](#papers)
- [工具和代码](#tools--code)
- [API](#apis)
- [数据集](#datasets)
- [模型](#models)
- [AI内容检测器](#ai-content-detectors)
- [教育](#educational)
  - [教程](#tutorials)
- [视频](#videos)
- [书籍](#books)
- [社区](#communities)
- [如何贡献](#how-to-contribute)


## 论文
📄
- **提示工程技术**:
  - [一个提示模式目录，增强 ChatGPT 的提示工程](https://arxiv.org/abs/2302.11382) [2023] (Arxiv)
  - [让硬提示容易：基于梯度的离散优化方法来进行提示调整和发现](https://arxiv.org/abs/2302.03668) [2023] (Arxiv)。- [合成提示：为大型语言模型生成思路演示](https://arxiv.org/abs/2302.00618) [2023] (Arxiv)
  - [渐进提示：用于语言模型的连续学习](https://arxiv.org/abs/2301.12314) [2023] (Arxiv)
  - [批量提示：使用 LLM API 进行高效推理](https://arxiv.org/abs/2301.08721) [2023] (Arxiv)
  - [连续提示用于解答复杂问题](https://arxiv.org/abs/2212.04092) [2022] (Arxiv)
  - [结构化提示：将上下文学习扩展到 1,000 个示例](https://arxiv.org/abs/2212.06713) [2022] (Arxiv)
  - [大型语言模型是人类级的提示工程师](https://arxiv.org/abs/2211.01910) [2022] (Arxiv)
  - [问我：一个为提示语言模型设计的简单策略](https://paperswithcode.com/paper/ask-me-anything-a-simple-strategy-for) [2022] (Arxiv)
  - [提示 GPT-3 成为可靠的模型](https://arxiv.org/abs/2210.09150) [2022](Arxiv)
  - [分解提示：一种解决复杂任务的模块化方法](https://arxiv.org/abs/2210.02406) [2022] (Arxiv)
  - [PromptChainer：通过视觉编程连接大语言模型的提示](https://arxiv.org/abs/2203.06566) [2022] (Arxiv)
  - [探究困惑模型中的提示工程](https://arxiv.org/abs/2211.15462) [2022] (Arxiv)
  - [展示你的工作：用于与语言模型进行中间计算的草稿](https://arxiv.org/abs/2112.00114) [2021] (Arxiv)
  - [转换指令提示以 GPTk 的语言形式呈现](https://arxiv.org/abs/2109.07830) [2021] (Arxiv)
  - [奇妙有序的提示及其发现方法：克服少样本提示顺序敏感性](https://arxiv.org/abs/2104.08786) [2021] (Arxiv)
  - [规模的力量：用于参数高效调整提示的方法](https://arxiv.org/abs/2104.08691) [2021] (Arxiv)
  - [大型语言模型的提示编程：超越少样本的范例](https://arxiv.org/abs/2102.07350) [2021] (Arxiv)- [Prefix-Tuning：优化连续提示生成](https://arxiv.org/abs/2101.00190) [2021] (Arxiv)

- **推理和上下文学习**：

  - [语言模型中的多模态思维链推理](https://arxiv.org/abs/2302.00923) [2023] (Arxiv)
  - [冷静思考之后，我们不妨不要一步一步地思考！零射击推理中的偏见和有毒行为](https://arxiv.org/abs/2212.08061) [2022] (Arxiv)
  - [ReAct：协同推理和行为的语言模型](https://arxiv.org/abs/2210.03629) [2022] (Arxiv)
  - [语言模型是贪婪的推理器：关于思维链的系统形式化分析](https://arxiv.org/abs/2210.01240v3) [2022] (Arxiv)
  - [关于使语言模型成为更好的推理器的进展](https://arxiv.org/abs/2206.02336) [2022] (Arxiv)
  - [大型语言模型是零射击推理器](https://arxiv.org/abs/2205.11916) [2022] (Arxiv)
  - [像程序执行者一样推理](https://arxiv.org/abs/2201.11473) [2022] (Arxiv)
  - [自一致性改善了语言模型的思维链推理](https://arxiv.org/abs/2203.11171) [2022] (Arxiv)
  - [重新思考演示的作用：是什么使上下文学习起作用？](https://arxiv.org/abs/2202.12837) [2022] (Arxiv)
  - [学会解释：通过思考链进行多模态推理，以回答科学问题](https://arxiv.org/abs/2209.09513v2) [2022] (Arxiv)
  - [思维链提示引发大型语言模型的推理](https://arxiv.org/abs/2201.11903) [2021] (Arxiv)
  - [生成知识提示进行常识推理](https://arxiv.org/abs/2110.08387) [2021] (Arxiv)
  - [BERTese:学习与BERT对话](https://aclanthology.org/2021.eacl-main.316) [2021] (Acl)

- **评估和改进语言模型**：

  - [大型语言模型很容易被无关上下文所分散注意力](https://arxiv.org/abs/2302.00093) [2023] (Arxiv)
  - [爬行语言模型的内部知识库](https://arxiv.org/abs/2301.12810) [2023] (Arxiv)- **使用模型编写的评估来发现语言模型的行为**：[2022] (Arxiv) 
  - [使用平滑法在使用之前进行校准：提高语言模型的少样本性能](https://arxiv.org/abs/2102.09690) [2021] (Arxiv) 
  
  
- **语言模型的应用**：

  - [多模态仇恨模因分类提示](https://arxiv.org/abs/2302.04156) [2023] (Arxiv) 
  - [PLACES：社交对话综合提示语言模型](https://arxiv.org/abs/2302.03269) [2023] (Arxiv) 
  - [基于常识的提示，用于可控的共情对话生成](https://arxiv.org/abs/2302.01441) [2023] (Arxiv) 
  - [PAL: 程序辅助语言模型](https://arxiv.org/abs/2211.10435) [2023](Arxiv) 
  - [用于多语言法律判断的法律提示工程](https://arxiv.org/abs/2212.02199) [2023] (Arxiv) 
  - [与Copilot进行对话：使用自然语言探索解决CS1问题的提示工程](https://arxiv.org/abs/2210.15157) [2022] (Arxiv) 
  - [Pre-Trained语言模型的剧情写作](https://aclanthology.org/2022.inlg-main.5) [2022] (Acl) 
  - [AutoPrompt：使用自动生成的提示从语言模型中引导知识](https://arxiv.org/abs/2010.15980) [2020] (Arxiv) 
  
  
- **威胁检测和对抗性示例**：

  - [宪法人工智能：AI反馈的无害性](https://arxiv.org/abs/2212.08073) [2022] (Arxiv) 
  - [忽略先前的提示：语言模型的攻击技术](https://arxiv.org/abs/2211.09527) [2022] (Arxiv) 
  - [机器生成的文本：威胁模型和检测方法的综合调查](https://arxiv.org/abs/2210.07321) [2022] (Arxiv) 
  - [通过手工制作的对抗性示例评估预先训练语言模型的易感性](https://arxiv.org/abs/2209.02128) [2022] (Arxiv) 
  - [基于生成提示的推理的毒性检测](https://arxiv.org/abs/2205.12390) [2022] (Arxiv)。- [如何知道语言模型知道什么？](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00324/96460/How-Can-We-Know-What-Language-Models-Know) [2020] (Mit) 


- **小样本学习和性能优化**：

  - [Promptagator：从8个示例中进行小样本稠密检索](https://arxiv.org/abs/2209.11755) [2022] (Arxiv) 
  - [几个样本提示推理的解释不可靠](https://arxiv.org/abs/2205.03401) [2022] (Arxiv) 
  - [使预训练的语言模型成为更好的小样本学习者](https://aclanthology.org/2021.acl-long.295) [2021] (Acl) 
  - [语言模型是小样本学习者](https://arxiv.org/abs/2005.14165) [2020] (Arxiv) 


- **文本到图像生成**：

  - [用于文本到图像生成的提示修饰符分类法](https://arxiv.org/abs/2204.13988) [2022] (Arxiv) 
  - [提示工程文本到图像生成模型的设计指南](https://arxiv.org/abs/2109.06977) [2021] (Arxiv)
  - [使用潜在扩散模型进行高分辨率图像合成](https://arxiv.org/abs/2112.10752) [2021] (Arxiv)
  - [DALL·E：从文本创建图像](https://arxiv.org/abs/2102.12092) [2021] (Arxiv)

- **文本到音乐/音频生成**：

  - [MusicLM：从文本生成音乐](https://arxiv.org/abs/2301.11325) [2023] (Arxiv) 
  - [ERNIE-Music：基于扩散模型的文本到波形音乐生成](https://arxiv.org/pdf/2302.04456) [2023] (Arxiv)
  - [Noise2Music：基于扩散模型的文本条件音乐生成](https://arxiv.org/abs/2301.11325) [2023) (Arxiv)
  - [AudioLM：一种基于语言建模的音频生成方法](https://arxiv.org/pdf/2209.03143) [2023] (Arxiv)
  - [Make-An-Audio：使用提示增强扩散模型的文本到音频生成](https://arxiv.org/pdf/2301.12661.pdf) [2023] (Arxiv)

- **文本到视频生成**：

  - [Dreamix：视频扩散模型是通用视频编辑器](https://arxiv.org/pdf/2302.01329.pdf) [2023] (Arxiv)- [Tune-A-Video: One-Shot 调谐图像扩散模型，用于文本到视频生成](https://arxiv.org/pdf/2212.11565.pdf) [2022] (Arxiv)
  - [Noise2Music: 带有扩散模型的文本条件音乐生成](https://arxiv.org/abs/2301.11325) [2023) (Arxiv)
  - [AudioLM: 一种语言建模方法用于音频生成](https://arxiv.org/pdf/2209.03143) [2023] (Arxiv)
  
- **概览**:

  - [Piloting Copilot and Codex: Hot Temperature, Cold Prompts, or Black Magic?](https://arxiv.org/abs/2210.14699) [2022] (Arxiv) 
  
  

## 工具和代码
🔧

|      名称                | 描述  | Url |
| :-------------------- | :----------: | :----------: |
| **GPT Index** | GPT Index是一个由数据结构集合组成的项目，旨在使大型外部知识库在LLMs中更易于使用。 | [[Github]](https://github.com/jerryjliu/gpt_index) |
| **Promptify** | 使用LLM解决NLP问题，并使用Promptify轻松为流行的生成模型（如GPT、PaLM等）生成不同的NLP任务提示 | [[Github]](https://github.com/promptslab/Promptify) |
| **Better Prompt** | 测试LLM提示的测试套件，然后将其推送到PROD | [[Github]](https://github.com/krrishdholakia/betterprompt) |
| **Interactive Composition Explorerx** | ICE 是一个 Python 库和语言模型程序的跟踪可视化器。| [[Github]](https://github.com/oughtinc/ice) |
| **LangChainx** | 通过组合性借助 LLM 来构建应用程序| [[Github]](https://github.com/hwchase17/langchain) |
| **OpenPrompt** | 一个用于学习提示的开源框架。| [[Github]](https://github.com/thunlp/OpenPrompt) |
| **Prompt Engine** | 该存储库包含用于创建和维护大型语言模型 (LLMs) 的提示的 NPM 实用程序库。 | [[Github]](https://github.com/microsoft/prompt-engine) |"| **PromptInject** | PromptInject 是一个框架，以模块化的方式组装提示信息，提供量化分析LLMs 对抗提示攻击的鲁棒性。 | [[Github]](https://github.com/agencyenterprise/PromptInject) |
| **Prompts AI** | GPT-3高级游乐场 | [[Github]](https://github.com/sevazhidkov/prompts-ai) |
| **Prompt Source** | PromptSource 是一个用于创建、共享和使用自然语言提示的工具包。 | [[Github]](https://github.com/bigscience-workshop/promptsource) |
| **ThoughtSource** | 用于机器思考的科学框架 | [[Github]](https://github.com/OpenBioLink/ThoughtSource) |


## APIs
💻

|      名称                | 描述  | 网址 | 付费还是开源 |
| :-------------------- | :----------: | :----------: | :----------: |
| **OpenAI** | 用于自然语言任务的 GPT-n，用于将自然语言转换为代码的 Codex，以及用于创建和编辑原始图像的 DALL·E | [[OpenAI]](https://openai.com/api/) | 付费 |
| **CohereAI** | Cohere 提供一种 API，通过该 API 可访问先进的大型语言模型和 NLP 工具。 | [[CohereAI]](https://cohere.ai/) | 付费 |
| **Anthropic** | 即将推出 | [[Anthropic]](https://www.anthropic.com/) | 付费 |
| **FLAN-T5 XXL** | 即将推出 | [[HugginFace]](https://huggingface.co/docs/api-inference/index) | 开源 |



## 数据集
💾

|      名称                | 描述  | 网址 |
| :-------------------- | :----------: | :----------: |
| **P3（Public Pool of Prompts）** | P3 是一个包含各种 NLP 任务的提示英文数据集集合。 | [[HuggingFace]](https://huggingface.co/datasets/bigscience/P3) |
| **Awesome ChatGPT Prompts** | 该仓库包括 ChatGPT 提示信息的策划，可更好地使用 ChatGPT。 | [[Github]](https://github.com/f/awesome-chatgpt-prompts)""| **写作提示** | 收集了一个由300K个人编写的故事与从一个在线论坛 (reddit) 中获取的写作提示组成的大型数据集 | [[Kaggle]](https://www.kaggle.com/datasets/ratthachat/writing-prompts) |
| **Midjourney提示** | 从MidJourney的公共Discord服务器中爬取的文本提示和图像URL | [[HuggingFace]](https://huggingface.co/datasets/succinctly/midjourney-prompts) |


## 模型
🧠

|      名称               | 描述 | Url |
| :-------------------- | :----------: | :----------: |
| **ChatGPT** | ChatGPT  | [[OpenAI]](https://chat.openai.com/) |
| **Codex** | Codex模型是我们GPT-3模型的后代，可以理解和生成代码。它们的训练数据包括来自GitHub的自然语言和数十亿行的公共代码 | [[Github]](https://platform.openai.com/docs/models/codex) |
| **Bloom** | BigScience大型开放科学开放获取多语言语言模型 | [[HuggingFace]](https://huggingface.co/bigscience/bloom) |
| **Facebook LLM** | OPT-175B是Meta训练的GPT-3等价模型。它是目前可用的最大预训练语言模型，拥有1750亿个参数。 | [[Alpa]](https://opt.alpa.ai/) |
| **GPT-NeoX** | GPT-NeoX-2TB是一个200亿参数的自回归语言模型，训练于Pile | [[HuggingFace]](https://huggingface.co/docs/transformers/model_doc/gpt_neox) |
| **FLAN-T5 XXL** | Flan-T5是一个指令调节模型，意味着它在prompt中获得指令时展现了零-shot行为 | [[HuggingFace/Google]](https://huggingface.co/google/flan-t5-xxl) |
| **XLM-RoBERTa-XL** | XLM-RoBERTa-XL模型在包含100种语言的2.5TB过滤后的CommonCrawl数据上进行了预训练 | [[HuggingFace]](https://huggingface.co/facebook/xlm-roberta-xxl) |
| **GPT-J** | 它是在Pile数据集上训练的类似于GPT-2的因果语言模型 | [[HuggingFace]](https://huggingface.co/docs/transformers/model_doc/gptj) |""| **PaLM-rlhf-pytorch** | RLHF（Reinforcement Learning with Human Feedback）模型在PaLM模型上的实现。基本上就是ChatGPT但是在PaLM模型上。 | [[Github]](https://github.com/lucidrains/PaLM-rlhf-pytorch) |
| **GPT-Neo** | 使用mesh-tensorflow库实现的模型并行GPT-2和GPT-3风格的模型。| [[Github]](https://github.com/EleutherAI/gpt-neo) |
| **LaMDA-rlhf-pytorch** | Google的LaMDA在PyTorch中的开源预训练实现，添加了与ChatGPT类似的RLHF功能。| [[Github]](https://github.com/conceptofmind/LaMDA-rlhf-pytorch) |
| **RLHF** | 从人类反馈中学习的强化学习（RLHF）模型的实现。 | [[Github]](https://github.com/xrsrke/instructGOOSE) |
| **GLM-130B** | GLM-130B:一种开放的双语预训练模型。 | [[Github]](https://github.com/THUDM/GLM-130B) |

## AI内容检测器
🔎

|      名称                | 描述  | 链接 | 
| :-------------------- | :----------: | :----------: |
| **AI文本分类器** | AI文本分类器是一个经过调优的GPT模型，它预测一段文本从各种来源（如ChatGPT）生成的可能性有多大。 | [[OpenAI]](https://platform.openai.com/ai-text-classifier) |
| **GPT-2输出检测器** | 这是GPT-2输出检测器模型的在线演示，基于🤗/Transformers RoBERTa的实现。 | [[HuggingFace]](https://huggingface.co/spaces/openai/openai-detector) |
| **Openai检测器** | 用于指示AI产生的文本的AI分类器（OpenAI检测器Python包装器）。 | [[GitHub]](https://github.com/promptslab/openai-detector) |



## 教程
📚

  - **提示工程介绍**

    - [提示工程101-介绍和资源](https://www.linkedin.com/pulse/prompt-engineering-101-introduction-resources-amatriain)
    - [Prompt Engineering 101](https://humanloop.com/blog/prompt-engineering-101)"。- [SudalaiRajkumar 的 Prompt 工程指南](https://github.com/SudalaiRajkumar/Talks_Webinars/blob/master/Slides/PromptEngineering_20230208.pdf)

  - **生成式语言模型入门指南**

    - [生成式语言模型初学者指南 - LaMBDA 指南](https://aitestkitchen.withgoogle.com/how-lamda-works)
    - [与 Cohere 一起使用生成式 AI：第 1 部分 - 模型提示](https://txt.cohere.ai/generative-ai-part-1)

  - **Prompt 工程最佳实践**

    - [使用 OpenAI API 进行 Prompt 工程的最佳实践](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
    - [如何编写良好的提示](https://andymatuschak.org/prompts)

  - **完整的 Prompt 工程指南**

    - [大型语言模型的 Prompt 工程完整介绍](https://www.mihaileric.com/posts/a-complete-introduction-to-prompt-engineering)
    - [Prompt 工程指南：如何设计完美的提示](https://richardbatt.co.uk/prompt-engineering-guide-how-to-engineer-the-perfect-prompts)

  - **Prompt 工程的技术方面**

    - [使用 GPT-3 进行 Prompt 工程的 3 个原则](https://www.linkedin.com/pulse/3-principles-prompt-engineering-gpt-3-ben-whately)
    - [一个 ChatGPT Prompt 工程的通用框架](https://medium.com/@thorbjoern.heise/a-generic-framework-for-chatgpt-prompt-engineering-7097f6513a0b)
    - [Prompt 编程的方法](https://generative.ink/posts/methods-of-prompt-programming)

  - **Prompt 工程资源**

    - [精选的 ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
    - [最佳 100+ 稳定的 Diffusion Prompts](https://mpost.io/best-100-stable-diffusion-prompts-the-most-beautiful-ai-text-to-image-prompts)
    - [DALLE Prompt 书](https://dallery.gallery/the-dalle-2-prompt-book)
    - [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
    - [Microsoft 的 Prompt 工程](https://microsoft.github.io/prompt-engineering)

## 视频
🎥.- [高级ChatGPT Prompt工程](https://www.youtube.com/watch?v=bBiTR_1sEmI)
- [ChatGPT: 5个初学者Prompt工程秘密](https://www.youtube.com/watch?v=2zg3V66-Fzs)
- [CMU高级自然语言处理 2022: 提问](https://youtube.com/watch?v=5ef83Wljm-M&feature=shares)
- [Prompt工程 - 一个新的职业吗？](https://www.youtube.com/watch?v=w102J3_9Bcs&ab_channel=PatrickDebois)
- [ChatGPT指南：用更好的提示将结果提高10倍](https://www.youtube.com/watch?v=os-JX1ZQwIA)
- [语言模型和Prompt工程：NLP中提示方法的系统调查](https://youtube.com/watch?v=OsbUfL8w-mo&feature=shares)
- [Prompt工程 101：自动完成、零样本、一次样本和少量样本提示](https://youtube.com/watch?v=v2gD8BHOaX4&feature=shares)


## 社群
🤝

- [OpenAI Discord](https://discord.com/invite/openai)
- [PromptsLab Discord](https://discord.gg/m88xfYMbK6)
- [学习Prompt](https://discord.gg/7enStJXQzD)
- [r/ChatGPT Discord](https://discord.com/invite/r-chatgpt-1050422060352024636)
- [MidJourney Discord](https://discord.com/invite/MidJourney)



# 如何贡献

我们欢迎为这个列表做出贡献！实际上，这也是我创建它的主要原因——鼓励贡献，让人们订阅变化，以便了解大型语言模型和提示工程领域的新的令人兴奋的发展。

在贡献之前，请花点时间查看我们的[贡献指南](contributing.md)。这些指南将有助于确保您的贡献与我们的目标相一致，并符合我们的质量和相关性标准。感谢您对参与这个项目的兴趣！


<h6 align="center">
<small><small>图片来源: docs.cohere.ai </small> </small>
</h6>".