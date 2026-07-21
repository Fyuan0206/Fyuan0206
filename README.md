<div align="center">

# Hi, I'm **此番言**

[中文](README.md) | [English](README_EN.md)

[![GitHub followers](https://img.shields.io/github/followers/Fyuan0206?logo=github&style=for-the-badge&color=0891b2&labelColor=1c1917)](https://github.com/Fyuan0206)
[![GitHub stars](https://img.shields.io/github/stars/Fyuan0206?style=for-the-badge&logo=github&color=0891b2&labelColor=1c1917)](https://github.com/Fyuan0206)
[![Profile Views](https://komarev.com/ghpvc/?username=Fyuan0206&style=for-the-badge&color=blueviolet)](https://github.com/Fyuan0206)

</div>

---

## 📫 Connect With Me

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-Fyuan0206-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Fyuan0206)
[![小红书](https://img.shields.io/badge/Rednote-此番言-e93c49?style=for-the-badge)](https://www.xiaohongshu.com/user/profile/611506480000000001004523)
[![知乎](https://img.shields.io/badge/知乎-此番言-0084FF?style=for-the-badge&logo=zhihu&logoColor=white)](https://www.zhihu.com/people/chen-ao-35-69)

</div>

---

## 🚀 个人作品

个人主导开发的项目（按仓库创建时间排序）：

### [**Ancient_Books**](https://github.com/Fyuan0206/Ancient_Books) · 2024-08

**项目背景**：中国大学生计算机设计大赛参赛作品 · **全国二等奖**

**解决问题**：古诗意境难懂、文言文晦涩、成语典故需多方查考，国学入门与学习成本较高。面向研究者、学生及传统文化爱好者，提供古诗赏析、文言翻译、成语解释、《论语》注释与《百家姓》解读等一站式古籍理解能力。

**技术栈**：InternLM2-7B 领域微调 · RAG 检索古籍语料 · 按任务类型（古诗赏析 / 文言翻译 / 成语 / 《论语》 / 《百家姓》）匹配 Prompt 模板生成解读

---

### [**Xinjing-LM**](https://github.com/Kedreamix/Xinjing-LM) · 2025-02

**项目背景**：GDC 2025 DeepSeek-Qwen 模型蒸馏极限挑战赛参赛作品 · **季军**

**解决问题**：心理健康咨询需求增长但专业资源有限，通用大模型缺乏心理学领域知识与安全对话能力。面向需要情绪疏导与心理学建议的用户，提供多轮共情对话与专业建议。

**技术栈**：Qwen 心理学领域微调 · 多源数据融合 + DeepSeek R1 数据蒸馏 · 情感类型 × 生活场景多轮对话构建 · LoRA / 全参数混合微调策略

---

### [**SelfAgent**](https://github.com/Fyuan0206/SelfAgent) · 2026-01

**项目背景**：AI+ 医疗项目作品

**解决问题**：专业心理咨询资源稀缺、成本高，情绪困扰难以及时获得支持。为无法随时接触专业服务的人群提供全天候 AI 情绪陪伴——融合文本 / 语音 / 图像多模态识别 12 种 DBT 核心情绪，按 L1 日常闲聊 / L2 DBT 干预 / L3 危机响应分级路由，并推荐 TIPP、STOP 等循证技能与 24 小时援助资源。

**技术栈**：CAMEL-AI 主 Agent 挂载情绪检测 / DBT 技能 / 危机协议 / 用户画像四类 Tool · 多模态输入融合 → 风险分级 → L1 日常对话 / L2 技能推荐 / L3 危机干预闭环

---

### [**Myietls-侃雅**](https://github.com/Fyuan0206/myietls) · 2026-03

**项目背景**：魔搭社区环球黑客松 AI Hackathon Tour 参赛作品

**解决问题**：雅思考生口语陪练与模考反馈难获取、成本高。覆盖 Part1 题库练习、AI 口语模考、即时评分与错题追踪，支持学生 / 教师 / 管理员完整学习闭环。

**技术栈**：Camel IELTS Agent 驱动模考多轮对话与四维口语评分 · Agentic RAG 按 Band 检索 Part1 题库 · 语音采集 → STT 转写 → Agent 评估反馈 → TTS 播报

---

### [**GoGoGo，出发喽**](https://github.com/Fyuan0206/GoGoGo) · 2026-05

**项目背景**：美团校园 AI Hackathon 大赛参赛作品

**解决问题**：深度游规划信息分散在攻略、评价、天气、交通等多源，人工拼路线耗时长且难兼顾个人偏好。用户一句自然语言需求，即可生成景观 / 摄影 / 经典环线 3 套可执行的甘肃丝路深度游方案。

**技术栈**：A0 总调度编排 12 个专业 Agent（意图 / 画像 / 攻略 / POI / 评价 / 餐饮 / 住宿 / 交通 / 天气 / 路线 / 质检）· SSE 实时推送各 Agent 执行进度 · POI 评分 + TrustScore + 路线优化输出 3 套可执行方案

---

### [**LearnFlow**](https://github.com/Fyuan0206/LearnFlow) · 2026-06

**项目背景**：Agent Builder Hackathon 深圳站参赛作品 · **二等奖**

**解决问题**：技术学习者面对海量资料，难以筛选、结构化吸收并转化为行动。输入一个学习主题，自动聚合资料、生成知识卡片与图谱、规划分阶段路径，并将要点拆解为可执行待办。

**技术栈**：LLM 编排服务链 · 主题输入 → 资料发现与 AI 摘要 → 知识卡片 / 图谱构建 → 分阶段学习路径规划 → 可执行待办拆解

---

## 🧩 开源项目

参与贡献的开源项目（按参与贡献时间排序）：

| 时间 | 项目 | 我的贡献 |
|:----:|:-----|:-----|
| 2024-06 | [**AMchat**](https://github.com/AXYZdong/AMchat)<br><sub>高等数学大模型</sub> | **项目贡献者** · 撰写 InternLM2-Math-Plus-20B 微调教程，参与 OpenXLab 在线体验应用部署与维护 |
| 2025-03 | [**hml-solutions**](https://github.com/datawhalechina/hml-solutions)<br><sub>动手学机器学习习题解答</sub> | **项目贡献者** · 撰写第 16 章概率图模型、第 17 章 EM 算法习题解答（含 Jupyter Notebook 与配图） |
| 2025-10 ~ 至今 | [**agentic-ai**](https://github.com/datawhalechina/agentic-ai)<br><sub>Agentic AI 中文教程</sub> | **项目负责人** · 统筹课程本地化与社区协作，主导第 4、5 章教程编写与翻译，维护多智能体工作流等章节，Review 合并社区 PR |
| 2026-01 | [**easy-vecdb**](https://github.com/datawhalechina/easy-vecdb)<br><sub>零基础向量数据库教程</sub> | **项目贡献者** · 撰写 project1「RAG with FAISS」实战教程（无框架依赖，含 Embedding / 向量检索 / LLM 完整代码） |
| 2026-01 ~ 2026-02 | [**self-llm**](https://github.com/datawhalechina/self-llm)<br><sub>开源大模型食用指南</sub> | **项目贡献者** · 撰写 Step-3.5-Flash SGLang 推理部署教程，补充昇腾平台 SGLang 教程 |
| 2026-02 ~ 至今 | [**agent-skills-with-anthropic**](https://github.com/datawhalechina/agent-skills-with-anthropic)<br><sub>Agent Skills 中文教程</sub> | **项目负责人** · 统筹课程章节规划与协作推进，组织多章节编写与维护，新增第 10 章总结，Review 合并社区 PR，维护 README 课程导航 |
| 2026-05 | [**ai-prompting-for-everyone**](https://github.com/datawhalechina/ai-prompting-for-everyone)<br><sub>AI Prompting 中文教程</sub> | **项目负责人** · 统筹 VitePress 文档站搭建与 GitHub Pages 自动部署，组织 Module 1 等章节翻译，维护站点结构与侧边栏导航 · [在线阅读](https://datawhalechina.github.io/ai-prompting-for-everyone/) |

---

## 📊 Activity

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=Fyuan0206)

![Snake animation](https://raw.githubusercontent.com/Fyuan0206/Fyuan0206/output/github-contribution-grid-snake-dark.svg)

</div>

---

## 📈 GitHub Stats

<div align="center">

<picture>
  <source
    srcset="https://github-readme-stats-one-bice.vercel.app/api?username=Fyuan0206&show_icons=true&icon_color=0366d6&bg_color=ffffff&hide_title=true&hide_border=true&include_all_commits=true&count_private=true&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR&exclude_repo=ijkplayer,flv.js,DanmakuFlameMaster,ailab,MagicaSakura,boxing,overlord,gengine,discovery,GoogleTranslate,Weibo-Picture-Store"
    media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" />
  <img
    src="https://github-readme-stats-one-bice.vercel.app/api?username=Fyuan0206&show_icons=true&icon_color=0366d6&bg_color=ffffff&hide_title=true&hide_border=true&include_all_commits=true&count_private=true&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR&exclude_repo=ijkplayer,flv.js,DanmakuFlameMaster,ailab,MagicaSakura,boxing,overlord,gengine,discovery,GoogleTranslate,Weibo-Picture-Store" />
</picture>

</div>
