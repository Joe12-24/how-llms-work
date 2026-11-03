# 大模型如何工作 · 训练 / 推理 / Agent

给 0 基础读者和前后端 / Agent 开发者的三幕互动教学页，纯前端、无后端。

**在线看：** https://joe12-24.github.io/how-llms-work/

## 内容
- 第 0 幕：30 秒直觉 — 大模型就是超级接龙机，只猜下一个词
- 第一幕 · 训练：语料 → Token → 猜词 → Loss → 梯度 → 更新参数；学习率滑杆 + Loss 曲线 + 单参数手算
- 第二幕 · 推理：分词 → Embedding → Attention 热力图 → 概率分布 → 温度采样 → 自回归逐词生成
- 第三幕 · Agent：while 循环（调模型 → 调工具 → 结果写回上下文），上下文增长、三大翻车点、RAG / Function Calling 祛魅、开发者伪代码

参考教学法：namiai.tech 的 training / matrix / matrix/agent 三页（同一小例子贯穿、逐步播放）。

## 技术
- 单文件 `index.html`，所有交互本地完成
- 部署：GitHub Pages（main 分支根目录）
