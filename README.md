
# ChatGLM 实践大赛参考资料

## 大赛信息

[ChatGLM 实践大赛](https://www.heywhale.com/home/global?search=ChatGLM%20%E5%AE%9E%E8%B7%B5%E5%A4%A7%E8%B5%9B&tab=competition)

## 参考-开源项目

### 0. 通用

| 序号 | 标题                                                                            | 介绍                                                                                    | Stars                                                                       |
| ---- | ------------------------------------------------------------------------------- |:--------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 1    | [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)                               | ChatGLM-6B: An Open Bilingual Dialogue Language Model 开源双语对话语言模型              | ![Github stars](https://img.shields.io/github/stars/THUDM/ChatGLM-6B.svg)   |
| 2    | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)                           | Chinese and English multimodal conversational language model 多模态中英双语对话语言模型 | ![Github stars](https://img.shields.io/github/stars/THUDM/VisualGLM-6B.svg) |
| 3    | [chatglm_finetuning](https://github.com/ssbuild/chatglm_finetuning)             | chatglm 6b finetuning and alpaca finetuning                                             | ![Github stars](https://img.shields.io/github/stars/ssbuild/chatglm_finetuning.svg) |
| 4    | [ChatGLM-Efficient-Tuning](https://github.com/hiyouga/ChatGLM-Efficient-Tuning) | Fine-tuning ChatGLM-6B with PEFT 基于 PEFT 的高效 ChatGLM 微调                          | ![Github stars](https://img.shields.io/github/stars/hiyouga/ChatGLM-Efficient-Tuning.svg) |
| 5    | [ChatGLM-webui](https://github.com/Akegarasu/ChatGLM-webui)                     | A WebUI for ChatGLM-6B                                                                  | ![Github stars](https://img.shields.io/github/stars/Akegarasu/ChatGLM-webui.svg) |

### 1. 论文学科分类（Easy）

介绍：根据标题和摘要将论文准确分类到 40 个自然学科中去，可能单学科，也可能交叉学科，准确度达到 90% 以上。
| 序号 | 标题 | 介绍 |  stars |
| ----| ---- | :----| ---- |
|      |      |      |                |

### 2. 问答式科研知识库（Medium）

介绍：将 PDF 论文上传构建向量化科研知识库，在知识库内做自由问答，要求相对回答专业，且答案后要附带相关文件。
| 序号 | 标题                                                                                | 介绍                                                                                          | stars |
| ---- | ----------------------------------------------------------------------------------- |:--------------------------------------------------------------------------------------------- | ----- |
| 1    | [langchain-ChatGLM](https://github.com/imClumsyPanda/langchain-ChatGLM)             | langchain-ChatGLM, local knowledge based ChatGLM with langchain 基于本地知识库的 ChatGLM 问答 | ![Github stars](https://img.shields.io/github/stars/imClumsyPanda/langchain-ChatGLM.svg)      |
| 2    | [LangChain-ChatGLM-Webui](https://github.com/thomas-yanxin/LangChain-ChatGLM-Webui) | 基于LangChain和ChatGLM-6B等系列LLM的针对本地知识库的自动问答                                  | ![Github stars](https://img.shields.io/github/stars/thomas-yanxin/LangChain-ChatGLM-Webui.svg)       |
| 3    | [wenda](https://github.com/wenda-LLM/wenda)                                         | 闻达：一个LLM调用平台。为小模型外挂知识库查找和设计自动执行动作，实现不亚于于大模型的生成能力 | ![Github stars](https://img.shields.io/github/stars/wenda-LLM/wenda.svg)      |

### 3. 论文综述和对比分析（Medium）

介绍：给定多篇论文的标题、摘要或全文，对论文的背景、问题、方法、实验、结论等进行综述或对比分析。
| 序号 | 标题                                                         | 介绍                                                                                                                                                                                                                                                                                     | stars                                                                       |
| ---- | ------------------------------------------------------------ |:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| 1    | [gpt_academic](https://github.com/binary-husky/gpt_academic) | 为GPT/GLM提供图形交互界面，特别优化论文阅读润色体验，模块化设计支持自定义快捷按钮&函数插件，支持代码块表格显示，Tex公式双显示，支持Python和C++等项目剖析&自译解功能，PDF/LaTex论文翻译&总结功能，支持并行问询多种LLM模型，支持清华chatglm等本地模型。兼容复旦MOSS, llama, rwkv, 盘古等。 | ![Github stars](https://img.shields.io/github/stars/binary-husky/gpt_academic.svg) |
| 2    | [pdfGPT](https://github.com/bhaskatripathi/pdfGPT)           | PDF GPT allows you to chat with the contents of your PDF file by using GPT capabilities. The only open source solution to turn your pdf files in a chatbot!                                                                                                                              | ![Github stars](https://img.shields.io/github/stars/bhaskatripathi/pdfGPT.svg)                                                                            |
| 3    | [ChatPaper](https://github.com/kaixindelele/ChatPaper)       | Use ChatGPT to summarize the arXiv papers. 全流程加速科研，利用chatgpt进行论文总结+润色+审稿+审稿回复                                                                                                                                                                                    |  ![Github stars](https://img.shields.io/github/stars/kaixindelele/ChatPaper.svg)                                                                           |

### 4. 投稿期刊会议推荐（Medium）

介绍：根据标题和摘要推荐适合的 Top K 期刊会议，并根据匹配度针对每个推荐期刊会议给出推荐理由。
| 序号 | 标题 | 介绍 |  stars |
| ----| ---- | :----| ---- |
|      |      |      |                |

### 5. 审稿回复（Medium）

介绍：基于 Openreview 数据，微调出一个审稿回复模型。
| 序号 | 标题 | 介绍 |  stars |
| ----| ---- | :----| ---- |
|      |      |      |                |

### 6. 论文检索（Hard）

介绍：给定概念、给定问题、给定实体等的单独和混合检索。
| 序号 | 标题 | 介绍 |  stars |
| ----| ---- | :----| ---- |
|      |      |      |                |

### 7. 论文推荐和科技情报生成（Hard）

介绍基于用户画像（订阅关键词+搜索浏览行为），从每日最新论文中筛选跟用户相关的1篇或多篇论文，基于论文信息（标题、作者、摘要等，也可以增加其他额外信息）微调大模型生成科技情报，情报形式和深度由选手自定义。
| 序号 | 标题 | 介绍 |  stars |
| ----| ---- | :----| ---- |
|      |      |      |                |

## 参考-其他参考

---

- [ChatGLM-6B 的部署与微调教程](https://www.heywhale.com/mw/project/6436d82948f7da1fee2be59e)
- [ChatGLM-6B 结合 langchain 实现本地知识库 QA Bot](https://www.heywhale.com/mw/project/643977aa446c45f4592a1e59)

## License

[![Creative Commons License](https://camo.githubusercontent.com/d7dc0d5330f990a89b7d8898102fa250b479415d38c925cb9a43ae4ed594fe6d/687474703a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792f342e302f38387833312e706e67)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
