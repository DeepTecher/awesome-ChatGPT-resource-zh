

# 中文 ChatGPT 精选资源清单  

![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) [![License](https://img.shields.io/github/license/DeepTecher/awesome-ChatGPT-resource-zh)](https://github.com/DeepTecher/awesome-ChatGPT-resource-zh/blob/master/LICENSE) [![Stars](https://img.shields.io/github/stars/DeepTecher/awesome-ChatGPT-resource-zh)](https://github.com/DeepTecher/awesome-ChatGPT-resource-zh) [![Issues](https://img.shields.io/github/issues/DeepTecher/awesome-ChatGPT-resource-zh)](https://github.com/DeepTecher/awesome-ChatGPT-resource-zh/issues)




ChatGPT模型是由[OpenAI](https://openai.com/)训练的大型语言模型，能够生成类人文本。 通过向它提供提示，它可以生成继续对话或扩展给定提示的响应。 我们都期待着它能够带来更多跨时代的改变。

> 精选 OpenAI 的 [ChatGPT](https://chat.openai.com) 和 GPT-3资源清单,  修改自 [humanloop/awesome-chatgpt](https://github.com/humanloop/awesome-chatgpt):fire:。此外将跟随最新资源以及添加中文相关的内容补充。

![ChatGPT](./imgs/chatgpt-header.png)

![ChatGPT img](./imgs/ChatGPT_Diagram.svg)

### 目录

- [GPT 通用资源](#gpt-通用资源)
- [ChatGPT 社区 / 讨论](#chatgpt-社区--讨论)
- [论文](#论文)
- [提示样例 （更好地让ChatGPT 回答出）](#提示样例-更好地让chatgpt-回答出)
- [大佬与大模型](#大佬与大模型)
- [其他厂商推出 or 计划竞品](#其他厂商推出-or-计划竞品)
- [视频讲解](#视频讲解)
- [API 工具](#api-工具)
- [Chrome 浏览器插件](#chrome-浏览器插件)
- [其他平台 ChatGPT 使用](#其他平台-chatgpt-使用)
- [社交工具](#社交工具)
- [应用](#应用)
- [命令行工具](#命令行工具)
- [Github Actions](#github-actions)


### GPT 通用资源

- [ChatGPT 官方APP](https://chat.openai.com)
  - [官方] ChatGPT Plus 已推出 `$20/month`
- [OpenAI API文档](https://beta.openai.com/docs)
- [ChatGPT 博客](https://openai.com/blog/chatgpt/)
- [ChatGPT 插件](https://openai.com/blog/chatgpt-plugins) `官方开放插件名单，使得ChatGPT具有更丰富、准确的结果`
- 非官方实现
  - **ColossalAI** [hpcaitech/ColossalAI](https://github.com/hpcaitech/ColossalAI/tree/main/applications/ChatGPT) :+1::+1::+1::+1::+1: [博客介绍](https://www.hpc-ai.tech/blog/colossal-ai-chatgpt)

### ChatGPT 社区 / 讨论
- [OpenAI | Discord 频道](https://discord.com/invite/openai)

### 论文
- 【OpenAI官方网站】[ChatGPT Blog](https://openai.com/blog/chatgpt/)  
- 【ChatGPTPro】[ChatGPTPro](https://chatgpt.pro/)  
- 【GPT-1论文】[Improving Language Understanding by Generative Pre-Training](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf)  
- 【GPT-2论文】[Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)  
- 【GPT-3论文】[Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)  
- 【InstructGPT论文】[Training language models to follow instructions with human feedback](https://arxiv.org/pdf/2203.02155.pdf)  
- 【RHLF论文】[Augmenting Reinforcement Learning with Human Feedback](https://www.cs.utexas.edu/~ai-lab/pubs/ICML_IL11-knox.pdf)  
- 【PPO算法论文】[Proximal Policy Optimization Algorithms](https://arxiv.org/abs/1707.06347) 
- 【InstructGPT 同期思想的论文】[Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback](https://arxiv.org/pdf/2204.05862.pdf)
- 【GPT-4 技术报告】[GPT-4 Technical Report](https://cdn.openai.com/papers/gpt-4.pdf) :fire:

### 提示样例 （更好地让ChatGPT 回答出）

- [英文版的ChatGPT调教指南](https://github.com/f/awesome-chatgpt-prompts)  :star::star::star::star::star:
- [中文版的ChatGPT调教指南](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)

### 大佬与大模型
> 近日，`ChatGPT`或者说是整个AI范式发生了变化，大佬们也开始着手在新的范式玩法上发力。我们期待着他们能够给我们带来更多成果。
- 贾扬清  [阿里离职报道链接](https://mp.weixin.qq.com/s/ErbtO1f4Tidd5n9-cWAtMg)
- 李沐 [创业公司 | Boson.ai](https://boson.ai/)
- 李开复 [Project AI 2.0](https://www.chuangxin.com/ai2) 相关报道：[筹办新公司，全球招英才](https://mp.weixin.qq.com/s/OVg6rbWEdq_JVEyboYdQpg)
- 杨红霞 [阿里达摩院 -> 字节 AI Lab](https://zhuanlan.zhihu.com/p/616112186)
- 王慧文 [收购国产AI框架OneFlow, 基建中国版ChatGPT](https://mp.weixin.qq.com/s/KESP2TAHhTkM5z1IhfoyvQ)

### 其他厂商推出 or 计划竞品
**谷歌 | [Bard](https://blog.google/technology/ai/bard-google-ai-search-updates/)**  :broken_heart: `2023.03.22 已重新开放，当前只支持美区和英区排队内测。当前只支持英文且不支持编码能力` [Bard 内测申请](https://bard.google.com/) `已可以访问。相比之前体验起来效果还是不错了`

<details>
<summary>更多介绍</summary>

<br>

- [机器之心 | 谷歌版ChatGPT Bard开放测试！我们已经体验上了](https://mp.weixin.qq.com/s/mbxMDuPaQLt5uXGh9kDtiQ)
- [量子位 | 谷歌版ChatGPT这次低调公测炸了！比GPT-4数学能力还强，体验名额发得很快，传送门在此](https://mp.weixin.qq.com/s/elgZMjqlSCT5S90I0nzKmg)
- [量子位 | 谷歌版ChatGPT灾难级发布，市值一夜狂跌7000亿，熬夜网友：退钱！](https://mp.weixin.qq.com/s/ErBVGG-HcdV1i6mIVPlwyg)
---

</details> 

**微软 | [BingGPT or EdgeGPT(暂且这么称呼把)]** `ChatGPT 和 GPT-3.5 提供支持`

<details>
<summary>更多介绍</summary>

<br>

- 【官方】[申请候补使用(PS:需通过使用微软 Edge 浏览器打开)](https://www.bing.com/new)
- 【官方】[微软旗下所有产品将全线整合ChatGPT...](https://mp.weixin.qq.com/s/w1r7zvtu19XCdzx75dWl4Q)
- [ API 调用方法](https://github.com/acheong08/EdgeGPT)
- [新智元 | 颠覆历史！「ChatGPT搜索引擎」发布，微软市值一夜飙涨5450亿](https://mp.weixin.qq.com/s/03EDC_Vl8SAM52oJvkX5SA)
- [独家丨拿到ChatGPT版Bing搜索的内测后，我觉得所有大厂都该慌了。](https://mp.weixin.qq.com/s/RUxpwL5Nf98GctgWdiLdVQ)
---

</details> 

**OpenAI | [GPT4](https://openai.com/research/gpt-4)** `多模态大模型，效果炸裂 Respect` [技术报告.pdf](https://cdn.openai.com/papers/gpt-4.pdf):+1::+1::+1::+1::+1:

<details>
<summary>更多介绍</summary>

<br>

- [量子位 | 微软：GPT-4下周发布，剑指多模态，可支持视频](https://mp.weixin.qq.com/s/tIBDwFD73CWpuBc9FTxEJQ)
- [机器之心 | GPT-4震撼发布：多模态大模型，直接升级ChatGPT、必应，开放API，游戏终结了？](https://mp.weixin.qq.com/s/kA7FBZsT6SIvwIkRwFS-xw)
- 【视频】【开发者演示】[【完整版】【双语字幕】3月15日GPT-4开发者演示直播24分钟完整版（GPT-4 Developer Livestream）](https://www.bilibili.com/video/BV1Qo4y1B7hJ/?spm_id_from=333.999.0.0)
- 【官方】[GPT-4 技术报告.pdf](https://cdn.openai.com/papers/gpt-4.pdf)
---

</details> 

**斯坦福 | [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)**  `性能媲美GPT-3.5，成本不到600美元`

<details>
<summary>更多介绍</summary>

<br>

- 【官方】[官网](https://crfm.stanford.edu/2023/03/13/alpaca.html)
- 【官方】[模型链接](https://crfm.stanford.edu/alpaca)
- 【官方】[GitHub 链接](https://github.com/tatsu-lab/stanford_alpaca)
- 【报道】[LeCun狂赞：600刀GPT-3.5平替！ 斯坦福70亿参数「羊驼」爆火，LLaMA杀疯了](https://mp.weixin.qq.com/s/ybVYZumZhk_yM_w0U1wXww)
---

</details> 

**Databricks | [Dolly](https://github.com/databrickslabs/dolly)**  `性能媲美GPT-3.5，60亿参数, 人工智能技术民主化道路上打响的第一弹。需要注意的是基础模型和数据集遵从协议` 😃

<details>
<summary>更多介绍</summary>

<br>

- 【官方】[官网](https://www.databricks.com/blog/2023/03/24/hello-dolly-democratizing-magic-chatgpt-open-models.html)
- 【官方】[GitHub 链接](https://github.com/databrickslabs/dolly)
- 【报道】[0门槛克隆ChatGPT！30分钟训完，60亿参数性能堪比GPT-3.5](https://mp.weixin.qq.com/s/RMrXIHGOy3cPu8ybQNWonA)
---

</details> 

**百度 | [文心一言 | ERNIE Bot](https://baike.baidu.com/item/%E6%96%87%E5%BF%83%E4%B8%80%E8%A8%80/62642976)** `已发布` 当前文心一言支持 `文学创作、商业文案创作、数理逻辑推理推算、中文理解、多模态生成`， 当前开放内测两种方式： 个人测试申请点[这里](https://yiyan.baidu.com/welcome), 企业测试点[这里](https://cloud.baidu.com/survey_summit/wenxin.html?track=C896034) 
<details>
<summary>更多介绍</summary>

<br>

- 【官方】[文心一言，3月16日见！](https://baijiahao.baidu.com/s?id=1759077896821259105&fromModule=lemma_middle-info)
- 【官方】[官宣：文心一言](https://mp.weixin.qq.com/s/0-8X9FPouteKzNiK6DPaiA)
- 【新闻时讯】[百度版ChatGPT文心一言3月完成内测对外开放..香港股价一度上涨13%，为三个月来最大涨幅](https://www.zaobao.com.sg/realtime/china/story20230207-1360557)
---

</details> 

**IDEA-CCNL | [封神榜|MindBot-Lite API](https://fengshenbang-lm.com/mindbot-lite)** `开放 API 测试` 对话指南参见[这里](https://mp.weixin.qq.com/s/Ihxegu_YW9jOkxW5ZAmauw)
<details>
<summary>更多介绍</summary>

<br>

- 【官方】[与MindBot-Lite唠嗑，你需要这份对话指南](https://mp.weixin.qq.com/s/Ihxegu_YW9jOkxW5ZAmauw)
---

</details>

**阿里 | [阿里版ChatGPT]** `已启动邀请内测` 2023.04.07 [开启邀测](https://mp.weixin.qq.com/s/olGY9Cm6hO1h8C9DSy7_qA)
<details>
<summary>更多介绍</summary>

<br>

- [阿里版ChatGPT已进入测试！中文聊天截图曝光，达摩院出品](https://mp.weixin.qq.com/s/xQmX9EnrKLAUxsEoCZXJVg)
- [阿里版ChatGPT突然上线邀测！大模型热战正剧开始，这是第一手体验实录](https://mp.weixin.qq.com/s/olGY9Cm6hO1h8C9DSy7_qA)
---

</details>

**腾讯 | [XXXX]** `类chatGPT相关方向已有布局，研究有序推进` 
<details>
<summary>更多介绍</summary>

<br>

- [腾讯：在ChatGPT和AIGC相关方向上有布局，专项研究有序推进](https://k.sina.com.cn/article_5044281310_12ca99fde02001ybg9.html#/)
---

</details>

**清华-THUDM | [[GitHub]ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)** `单卡版推理模型开源，大模型内测启动, 效果还不错`  内测申请[这里](https://chatglm.cn/login), 博客介绍[这里](https://chatglm.cn/blog)
<details>
<summary>更多介绍</summary>

<br>

- 【官方】[ChatGLM：千亿基座的对话模型开启内测](https://chatglm.cn/blog)
- [ChatGLM：千亿基座的对话模型启动内测，单卡版模型已全面开源](https://zhuanlan.zhihu.com/p/613862055)
- 【知乎问题】[如何评价智谱 AI 发布的 ChatGLM，以及开源支持单卡推理的 ChatGLM-6B 模型？](https://www.zhihu.com/question/589484629/answer/2935869281)
---

</details>

**清华 | [Cpm-Bee](https://live.openbmb.org/models/bee)**  `开放网页测试，非InstructGPT框架，暂未支持多轮对话能力，计划3月份released`

<details>
<summary>更多介绍</summary>

<br>

- 【官方】[登顶 ZeroCLUE！CPM-Bee 凭什么这样强？](https://mp.weixin.qq.com/s/5NEYk0xQu0CqTkqu5o6rhg)
- 【官方】[小工具撬动大模型，『模力表格』惊喜问世](https://mp.weixin.qq.com/s/XoQN-QQhzWZAPdw7EKBuUg)
---

</details> 

**科大讯飞 | [XXX]** `紧急开发，暂未发布, 预计5月6号跟随落地场景released`
<details>
<summary>更多介绍</summary>

<br>

- [科大讯飞被曝加紧开发中国版ChatGPT，具体发布时间已确定](https://mp.weixin.qq.com/s/o8D9GGlkmJ_RvaDL9filEQ)
---

</details>


**复旦 | [类ChatGPT](https://moss.fastnlp.top/)** `邀请公众内测; 实验室无法做出和 ChatGPT 能力相近的模型，MOSS 只是想在百亿规模参数上探索和验证 ChatGPT 的技术路线，并且实现各种对话能力。` 拟[3月底开源](https://finance.sina.com.cn/jjxw/2023-02-26/doc-imyhzxxr5017027.shtml)

<details>
<summary>更多介绍</summary>

<br>

- 【报道】[复旦教授邱锡鹏：MOSS大模型拟3月底开源](https://finance.sina.com.cn/jjxw/2023-02-26/doc-imyhzxxr5017027.shtml)
- 【报道】[复旦团队发布国内首个类ChatGPT模型MOSS，邀公众参与内测](https://www.shobserver.com/staticsg/res/html/web/newsDetail.html?id=584634)
- 【报道】[复旦MOSS团队致歉：还不成熟，没想到引起这么大的关注](https://www.toutiao.com/article/7202413664077644322/?tt_from=weixin&utm_campaign=client_share&app=news_article&utm_source=weixin&iid=0&utm_medium=toutiao_ios&share_token=F48B4299-E9E1-4801-9582-1C69E12CD4DE&wxshare_count=2&source=m_redirect&wid=1676944293806)
- 【知乎相关提问】[复旦团队发布国内首个类 ChatGPT 模型 MOSS，将为国内大语言模型的探索和应用带来哪些影响?](https://www.zhihu.com/question/585248111)
---

</details> 

**哈工大 | [相关研究报告](./pdfs/230311-哈尔滨工业大学-ChatGPT调研报告.pdf)**

<details>
<summary>更多介绍</summary>
<br>

- 【报告】[230311-哈尔滨工业大学-ChatGPT调研报告.pdf](./pdfs/230311-哈尔滨工业大学-ChatGPT调研报告.pdf)

</details> 

**| [海豚AI写作助手](http://zhimachat.com/)** `国内首个可供体验的类ChatGPT模型`

<details>
<summary>更多介绍</summary>
<br>

- 【官方】[体验链接](http://zhimachat.com/)

</details> 

**360 | [360版ChatGPT 雏形产品]** `并非真正意义上的产品发布，只是向观众演示目前的产品雏形，股票上涨7%左右`

<details>
<summary>更多介绍</summary>
<br>

- 【报道】[周鸿祎演示自研类ChatGPT模型 现场回答观众多个问题](https://baijiahao.baidu.com/s?id=1761700815878234195&wfr=spider&for=pc)

</details> 

### 视频讲解
- 【李宏毅】[B站 ChatGPT讲解合集](https://www.bilibili.com/video/BV1yL411D72E/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb)。包含：
    - [B站链接直达](https://www.bilibili.com/video/BV1yL411D72E/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb&t=0) ChatGPT (可能)是怎麼煉成的 - GPT 社會化的過程     
    - [B站链接直达](https://www.bilibili.com/video/BV1yL411D72E/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb&t=1077)李宏毅2023春机器学习课程: 【生成式AI】ChatGPT原理剖析（1/3）对Chat GPT的常见误解
    - [B站链接直达](https://www.bilibili.com/video/BV1yL411D72E/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb&t=2282) 李宏毅2023春机器学习课程: 【生成式AI】ChatGPT原理剖析（2/3）预训练（Pre-Train）
    - [B站链接直达](https://www.bilibili.com/video/BV1yL411D72E/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb&t=3873) 李宏毅2023春机器学习课程: 【生成式AI】ChatGPT原理剖析（3/3）ChatGPT所带来的研究问题

- 【陈縕侬】[B站 ChatGPT讲解合集](https://www.bilibili.com/video/BV1gs4y1H7nC/?spm_id_from=333.788.recommend_more_video.-1&vd_source=71b548de6de953e10b96b6547ada83f2)
  - [B站链接直达](https://www.bilibili.com/video/BV1gs4y1H7nC/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb&t=0) (1) InstructGPT(2022)
  - [B站链接直达](https://www.bilibili.com/video/BV1gs4y1H7nC/?share_source=copy_web&vd_source=ca4121edeb864fc9d85abd1506c1dfeb&t=1514) (2) ChatGPT(2022)

- 【李沐】
  - [B站链接直达](https://www.bilibili.com/video/BV1hd4y187CR/?spm_id_from=333.788&vd_source=71b548de6de953e10b96b6547ada83f2) InstructGPT 论文精读【论文精读·48】
  - [B站链接直达](https://www.bilibili.com/video/BV1XY411B7nM/?spm_id_from=333.999.0.0) Anthropic LLM 论文精读【论文精读·51】

- 【李宏毅】[【生成式AI】【李宏毅】GPT-4 來了! GPT-4 這次有什麼神奇的能力呢？](https://www.bilibili.com/video/BV1SL411R7r1/?spm_id_from=333.337.search-card.all.click&vd_source=71b548de6de953e10b96b6547ada83f2)
-  【GPT-4 官方演示视频】[3月15日GPT-4开发者演示直播24分钟完整版（GPT-4 Developer Livestream）](https://www.bilibili.com/video/BV1Qo4y1B7hJ/?spm_id_from=333.999.0.0)

### API 工具

- [【非官方】【Python】 acheong08/ChatGPT ](https://github.com/acheong08/ChatGPT)
- [【非官方】【Python】 rawandahmad698/PyChatGPT ](https://github.com/rawandahmad698/PyChatGPT)
- [【非官方】【JS/TS】 transitive-bullshit/chatgpt-api ](https://github.com/transitive-bullshit/chatgpt-api)
- [【非官方】【Dart】 MisterJimson/chatgpt_api_dart](https://github.com/MisterJimson/chatgpt_api_dart)


### Chrome 浏览器插件
- [插件：在任何页面上以弹出窗口的形式访问 ChatGPT](https://github.com/kazuki-sf/ChatGPT_Extension)
- [插件: 在 Google 搜索结果旁边显示 ChatGPT 响应](https://github.com/wong2/chat-gpt-google-extension)
- [插件: 将你与ChatGPT对话保存为 PNG, PDF 或 可分享的链接](https://github.com/liady/ChatGPT-pdf)
- [插件：在ChatGPT中添加输入历史, 复制和计数等功能](https://chrome.google.com/webstore/detail/superpower-chatgpt/amhmeenmapldpjdedekalnfifgnpfnkc)
- [ChassistantGPT - 将chatGPT嵌入作为语音助手](https://github.com/idosal/assistant-chat-gpt)
- [WebChatGPT - 加入web 搜索结果选项](https://github.com/qunash/chatgpt-advanced/)

### 其他平台 ChatGPT 使用
- [【微信】 迅速接入 ChatGPT，让它成为你最好的助手！](https://github.com/fuergaosi233/wechat-chatgpt)
- [【微信】 bot ](https://github.com/AutumnWhj/ChatGPT-wechat-bot)
- [【Telegram】 bot](https://github.com/franalgaba/chatgpt-telegram-bot-serverless)
- [【WhatsApp】 bot](https://github.com/danielgross/whatsapp-gpt)
- [【RayCast】插件  (非官方)](https://github.com/abielzulio/chatgpt-raycast)
- [【VSCode】插件](https://github.com/mpociot/chatgpt-vscode) ([demo](https://twitter.com/marcelpociot/status/1599180144551526400))
- [【Telegram】 bot - GO语言](https://github.com/m1guelpf/chatgpt-telegram)
- [【Twitter】 bot](https://github.com/transitive-bullshit/chatgpt-twitter-bot) 
- [ Google 文档](https://github.com/cesarhuret/docGPT)
- [ Mac平台 菜单应用](https://github.com/vincelwt/chatgpt-mac)
- [ 多平台(Windows, Mac, Linux)应用](https://github.com/lencx/ChatGPT)  :star::star::star::star::star:ChatGPT & Tauri
- [【非官方】 Windows, Mac, Linux 桌面app](https://github.com/sonnylazuardi/chatgpt-desktop)
- [【Jetbrains IDEs】插件](https://github.com/LiLittleCat/intellij-chatgpt)
- [【Slack Bot】](https://github.com/pedrorito/ChatGPTSlackBot)
- [【Discord Bot】](https://github.com/m1guelpf/chatgpt-discord)


### 社交工具
- [shareGPT - 一键分享你与ChatGPT对话记录](https://github.com/domeccleston/sharegpt)

### 应用
- [ChatARKit: 使用 ChatGPT 的 自然语言生成能力创建 AR 体验](https://github.com/trzy/ChatARKit)
- [DeepWrite AI：博客发布生成器](https://github.com/simplysabir/AI-Writing-Assistant)
- [修复代码错误并解释错误](https://github.com/shobrook/adrenaline/)
- [将chatGPT prompt 作用 stable diffusion](https://github.com/hallatore/stable-diffusion-webui-chatgpt-utilities)

### 命令行工具 
- [chatgpt-conversation: 用声音与 ChatGPT 对话，并让其回应](https://github.com/platelminto/chatgpt-conversation)
- [用 ChatGPT解释你运行时的错误](https://github.com/shobrook/stackexplain)
- [GPT3 WordPress 帖子生成器](https://github.com/nicolaballotta/gtp3-wordpress-post-generator)
- [命令行助手](https://github.com/diciaup/assistant-cli)

### Github Actions
- [ChatGPT Code Review](https://github.com/kxxt/chatgpt-action)



---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=DeepTecher/awesome-ChatGPT-resource-zh&type=Timeline)](https://star-history.com/#DeepTecher/awesome-ChatGPT-resource-zh&Timeline)

### 参考

* [humanloop/awesome-chatgpt](https://github.com/humanloop/awesome-chatgpt) 
* [dalinvip/Awesome-ChatGPT](https://github.com/dalinvip/Awesome-ChatGPT) 
