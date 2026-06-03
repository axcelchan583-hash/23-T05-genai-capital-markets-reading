# GenAI x Stock / Capital Markets 全景阅读清单

整理日期：2026-06-02

用途：给主人用一周时间系统理解 GenAI + stock / capital markets 的理论、前人工作和可迁移研究设计。

说明：
- 三篇已精读的 Qian / Ecker / Cheng 见 `docs/reference_reading/01_three_genai_stock_papers_close_reading_and_qian_replication_diagnosis_20260602.md`。
- 标签含义：`已发表`、`forthcoming/accepted`、`working paper`、`低优先级`、`谨慎引用`。
- 这份清单不只服务 T05 投稿，而是先建立领域地图；引用前仍要核对最新期刊状态、卷期、DOI 和是否撤稿。

---

## 一、一周阅读顺序

Day 1：读综述和总地图
- Eisfeldt & Schubert, *Generative AI and Finance*
- Mo & Ouyang, *(Generative) AI in Financial Economics*

Day 2：GenAI 作为技术冲击和公司价值重估
- Eisfeldt et al., *Generative AI and Firm Values*
- Babina et al., *Artificial Intelligence, Firm Growth, and Product Innovation*

Day 3：LLM 是否能预测股票收益 / 改变价格发现
- Lopez-Lira & Tang, *Can ChatGPT Forecast Stock Price Movements?*
- Chen, Kelly & Xiu, *Expected Returns and Large Language Models*
- Chen, Tang, Zhou & Zhu, *ChatGPT and DeepSeek: Can They Predict the Stock Market and Macroeconomy?*

Day 4：投资者真实使用 GenAI 和交易行为
- Ecker et al., *How Stock Market Participants Use Generative Artificial Intelligence*
- Cheng et al., *Does Generative AI Facilitate Investor Trading?*
- Chang et al., *AI Democratization and Trading Inequality*
- Blankespoor, Croom & Grant, *Generative AI and Investor Processing of Financial Information*

Day 5：信息中介、分析师、资产管理
- Bradshaw et al., *Generative AI Use by Capital Market Information Intermediaries*
- Sheng et al., *Generative AI and Asset Management*
- Cao et al., *From Man vs. Machine to Man + Machine*
- Xue, Zhang & Zhu, *Generative AI for Analysts*（working paper，跟踪）

Day 6：披露、公告和关联公司反应
- Qian et al., *The Impact of Generative AI Announcements on Suppliers*
- Blankespoor, deHaan & Li, *Generative AI in Financial Reporting*
- Cao et al., *Can Generative AI Help Identify Peer Firms?*

Day 7：整理矩阵
- 每篇记录：研究问题、X、Y、识别、数据、机制、局限、对中国 A 股/T05 的可迁移性。

---

## 二、核心顶刊 / 高可信已发表与已接收

1. **Eisfeldt, A. L., Schubert, G., Zhang, M. B., & Taska, B.** — *Generative AI and Firm Values*
   - 状态：Journal of Finance forthcoming / accepted
   - 标识：SSRN 4436627 / 4440717；NBER WP 31222；JF DOI 待核对
   - 一句话：构造企业劳动力 GenAI 暴露，ChatGPT 发布后高暴露企业组合获得显著正向短窗回报；主要解释为劳动替代和生产率预期。
   - 用途：GenAI 作为外生技术冲击和 firm value revaluation 的主锚。

2. **Lopez-Lira, A., & Tang, Y.** — *Can ChatGPT Forecast Stock Price Movements? Return Predictability and Large Language Models*
   - 状态：Journal of Financial Economics forthcoming
   - 标识：SSRN 4412788；arXiv 2304.07619
   - 一句话：GPT 从新闻标题提取市场含义，预测后续收益，尤其是小盘、负面新闻和复杂文本。
   - 用途：LLM 降低信息处理成本、改善价格发现的核心文献。

3. **Bertomeu, J., Lin, Y., Liu, Y., & Ni, Z.** — *The Impact of Generative AI on Information Processing: Evidence from the Ban of ChatGPT in Italy*
   - 状态：Journal of Accounting and Economics, 2025, 80(1): 101782
   - 标识：DOI 10.1016/j.jacceco.2025.101782；SSRN 5118661 / 4452670
   - 一句话：利用意大利 ChatGPT 禁令，识别 GenAI 可得性下降如何影响分析师预测、信息不对称和市场效率。
   - 用途：GenAI access 作为信息处理能力冲击的顶刊识别锚。

4. **Cheng, Q., Lin, P., & Zhao, Y.** — *Does Generative AI Facilitate Investor Trading? Early Evidence from ChatGPT Outages*〔已精读=C〕
   - 状态：Journal of Accounting and Economics, 2025, 80(2-3): 101821
   - 标识：DOI 10.1016/j.jacceco.2025.101821
   - 一句话：ChatGPT 宕机期间交易量下降；有公司新闻和 transient institutional ownership 的股票更敏感。
   - 用途：投资者确实依赖 GenAI 处理交易相关信息的因果证据。

5. **Ecker, F., Li, X., Li, Y., & Wu, F.** — *How Stock Market Participants Use Generative Artificial Intelligence: Evidence from User-Platform Interaction Data*〔已精读=B〕
   - 状态：Journal of Accounting Research, 2026
   - 标识：DOI 10.1111/1475-679X.70051
   - 一句话：中国 174 万条选股 query 显示投资者围绕公司披露、媒体覆盖和交易信号使用 GenAI。
   - 用途：中国制度背景 + 投资者真实 GenAI 使用行为 + 信息加工机制主锚。

6. **Bradshaw, M. T., Ma, C., Yost, B. P., & Zou, Y.** — *Generative AI Use by Capital Market Information Intermediaries: Evidence from Seeking Alpha*
   - 状态：Journal of Accounting Research forthcoming
   - 标识：SSRN 5226562；HBS Working Paper 25-055
   - 一句话：Seeking Alpha 上 AI 文章增加作者生产率和公司覆盖，但单篇 AI 文章市场反应弱于人工文章。
   - 用途：GenAI 改造信息中介的核心文献；“低成本广覆盖 vs 单篇质量折损”的重要张力。

7. **Chang, A. Y., Dong, X., Martin, X., & Zhou, C.** — *AI Democratization and Trading Inequality*
   - 状态：Journal of Accounting Research forthcoming
   - 标识：SSRN 4543999
   - 一句话：ChatGPT 普及后，散户交易更接近 AI sentiment 信号，信息不对称下降，散户交易表现改善。
   - 用途：GenAI democratization、retail investors、trading inequality 的核心文献。

8. **Croom, J.** — *Interactivity and Illusions of Ability: How Using Generative AI Affects Investor Judgments*
   - 状态：Journal of Accounting Research forthcoming
   - 标识：SSRN 4852574；DOI 10.1111/1475-679X.70017
   - 一句话：GenAI 的交互性会让投资者高估自身能力并提高投资意愿，但不一定改善实际处理质量。
   - 用途：GenAI 降低处理成本之外的行为偏差机制。

9. **Sheng, J., Sun, Z., Yang, B., & Zhang, A. L.** — *Generative AI and Asset Management*
   - 状态：Review of Financial Studies forthcoming
   - 标识：SSRN 4786575
   - 一句话：hedge funds 采用 GenAI 后异常收益提升，优势来自 AI talent 和 GenAI 分析公司特定信息的能力。
   - 用途：专业投资者/资产管理机构采用 GenAI 的核心文献。

10. **Qian, Z., Peng, J., & Li, J.** — *The Impact of Generative AI Announcements on Suppliers: Evidence from the Stock Market*〔已精读=A〕
    - 状态：Production and Operations Management, 2025/2026
    - 标识：DOI 10.1177/10591478251398333；SSRN 4957042
    - 一句话：客户 GenAI 公告带来上游供应商正向异常收益。
    - 用途：GenAI announcement spillover；对 T05 是供应链正向验证与横向竞争负向重估的 foil。

11. **Babina, T., Fedyk, A., He, A., & Hodson, J.** — *Artificial Intelligence, Firm Growth, and Product Innovation*
    - 状态：Journal of Financial Economics, 2024, 151: 103745
    - 标识：DOI 10.1016/j.jfineco.2023.103745；SSRN 3651052
    - 一句话：用简历构造 firm-level AI investment，AI 企业增长、产品创新和行业集中度更强。
    - 用途：广义 AI adoption / AI hiring measurement 的经典锚；非 GenAI，但必须读。

12. **Cao, S., Jiang, W., Wang, J., & Yang, B.** — *From Man vs. Machine to Man + Machine: The Art and AI of Stock Analyses*
    - 状态：Journal of Financial Economics, 2024, 160: 103910
    - 标识：DOI 10.1016/j.jfineco.2024.103910
    - 一句话：AI analyst 能超过多数人类分析师，但 human + machine 能降低极端错误并保留制度知识优势。
    - 用途：stock analysis 自动化、人机互补、信息中介生产函数变化的前置顶刊锚。

13. **Cao, Y., Chen, L., Tucker, J. W., & Wan, C.** — *Can Generative AI Help Identify Peer Firms?*
    - 状态：Review of Accounting Studies, 2025
    - 标识：DOI 10.1007/s11142-025-09892-6；SSRN 4761624
    - 一句话：GenAI 识别的 peer firms 与专家/传统系统重合，并在未来收益、销售增长和毛利率上表现出更强相关性。
    - 用途：LLM peer identification 的直接方法锚；对 T05 的 peer definition 风险尤其重要。

14. **Eisfeldt, A. L., & Schubert, G.** — *Generative AI and Finance*
    - 状态：Annual Review of Financial Economics, 2025, 17: 363-393
    - 标识：DOI 10.1146/annurev-financial-112923-020503
    - 一句话：综述 GenAI 对金融职业、公司价值、资产管理和金融研究方法的影响。
    - 用途：Day 1 文献地图 / 引言总括。

---

## 三、高质量 working papers / 需要跟踪状态

15. **Chen, Y., Kelly, B. T., & Xiu, D.** — *Expected Returns and Large Language Models*
    - 状态：working paper
    - 标识：SSRN 4416687
    - 一句话：用 LLM 从全球金融新闻抽取信号，预测 16 个市场、13 种语言下的股票收益。
    - 用途：LLM return prediction 的大样本、多市场锚。

16. **Jha, M., Qian, J., Weber, M., & Yang, B.** — *ChatGPT and Corporate Policies*
    - 状态：NBER working paper
    - 标识：NBER WP 32161；DOI 10.3386/w32161；SSRN 4521096；arXiv 2409.17933
    - 一句话：用电话会构造 firm-level ChatGPT investment score，预测未来 capex、R&D、无形投资和收益。
    - 用途：LLM 从管理层语言中提取公司政策预期的核心工作论文。

17. **Blankespoor, E., Croom, J., & Grant, S. M.** — *Generative AI and Investor Processing of Financial Information*
    - 状态：working paper
    - 标识：SSRN 5053905
    - 一句话：用券商 GenAI chatbot 查询和 2000 多名散户调查，描述散户如何用 GenAI 解释、筛选和监控金融信息。
    - 用途：投资者真实使用场景；补足 Ecker 的平台数据外部证据。

18. **Blankespoor, E., deHaan, E., & Li, Q.** — *Generative AI in Financial Reporting*
    - 状态：working paper / 期刊状态需核对
    - 标识：SSRN 4986017
    - 一句话：检测企业在 earnings press releases、conference call prepared remarks、risk factors、MD&A、S-1 中使用 GenAI 写作。
    - 用途：公司披露生产端 GenAI adoption；和 T05 的披露文本直接相关。

19. **Chen, J., Tang, G., Zhou, G., & Zhu, W.** — *ChatGPT and DeepSeek: Can They Predict the Stock Market and Macroeconomy?*
    - 状态：arXiv / submitted，需跟踪
    - 标识：arXiv 2502.10008
    - 一句话：比较 ChatGPT、DeepSeek 等模型从 WSJ 新闻中预测市场收益和宏观变量的能力。
    - 用途：模型差异、英文语料优势、DeepSeek 相关讨论的参考。

20. **Bond, S. A., Klok, H., & Zhu, M.** — *Large Language Models and Financial Market Sentiment*
    - 状态：working paper
    - 标识：SSRN 4584928
    - 一句话：用 ChatGPT 构造 S&P 500 市场情绪指标，比较传统情绪分类器与 LLM。
    - 用途：aggregate sentiment / market-level prediction 旁支。

21. **Chen, S., Peng, L., & Zhou, D.** — *Wisdom or Whims? Decoding Investor Trading Strategies with Large Language Models*
    - 状态：working paper，题名版本可能变化
    - 标识：作者主页 / ABFER 版本；引用前核对 SSRN 或最新稿
    - 一句话：用 LLM 分类 7700 万条投资者社媒信息中的技术分析、基本面分析和其他策略。
    - 用途：GenAI/LLM 作为研究工具识别 retail investor strategy。

22. **Xue, J., Zhang, Q., & Zhu, W.** — *Generative AI for Analysts*
    - 状态：working paper / revise & resubmit 信息需核对
    - 标识：作者主页 / seminar version
    - 一句话：利用 FactSet AI 平台上线作为自然实验，分析 GenAI 如何改变分析师报告的信息来源、覆盖广度、方法复杂度、及时性和预测误差。
    - 用途：sell-side analyst workflow 被 GenAI 改造的前沿工作。

23. **Li, E. X., Tu, Z., & Zhou, D.** — *The Promise and Peril of Generative AI: Evidence from GPT as Sell-Side Analysts*
    - 状态：working paper
    - 标识：SSRN 4480947
    - 一句话：评估 GPT 作为卖方分析师的能力与风险。
    - 用途：和 Man + Machine、Generative AI for Analysts 组成分析师主题补充阅读。

---

## 四、中国市场 / 低优先级但有场景价值

24. **How investors' ChatGPT attention influence stock market? A liquidity perspective**
    - 状态：Research in International Business and Finance, 2025
    - 标识：DOI 10.1016/j.ribaf.2025.102939
    - 一句话：用中国投资者互动平台 GPT 相关提问衡量 ChatGPT attention，发现其与股票流动性改善相关。
    - 用途：中国 IIP/互动平台场景；期刊层级一般，做背景或对照即可。

25. **Wu, Y., Tian, M., & Tang, G.** — *Does Generative AI Impact Stock Price Crash Risk? Evidence from China*
    - 状态：working paper / 低优先级
    - 标识：SSRN 4961724 / 4946226
    - 一句话：用 ERNIE Bot 发布研究中国市场股价崩盘风险变化。
    - 用途：中国 GenAI 事件研究旁支；暂不建议作为主文献。

26. **Pietrzak, M.** — *A Trillion Dollars Race: How ChatGPT Affects Stock Prices*
    - 状态：Future Business Journal, 2025 / 低优先级
    - 标识：SSRN 4586428；publisher DOI 需核对
    - 一句话：研究 ChatGPT 相关公司公告对美国上市公司短窗异常收益的影响。
    - 用途：普通 announcement event-study 参考；期刊层级不足，不作主锚。

---

## 五、谨慎引用 / 不作核心证据

27. **Kim, A., Muhn, M., & Nikolaev, V.** — *Bloated Disclosures: Can ChatGPT Help Investors Process Information?*
    - 状态：withdrawn / 谨慎引用
    - 标识：SSRN 4425527；arXiv 2306.10224
    - 一句话：原始版本声称 GPT 摘要更短且更能解释市场反应，但 arXiv 已显示撤回说明。
    - 用途：只作为研究方向和复制风险案例；不要当稳定实证证据引用。

28. **Kim, A., Muhn, M., & Nikolaev, V.** — *Financial Statement Analysis with Large Language Models*
    - 状态：withdrawn / 谨慎引用
    - 标识：arXiv 2407.17866
    - 一句话：原始版本声称 LLM 可仅凭标准化财报预测盈余方向并超过分析师基准，但 arXiv 已显示撤回说明。
    - 用途：只作为“LLM 财务分析结果需要复制验证”的警示案例。

---

## 六、检索建议

```text
关键词：
    ChatGPT, large language models, LLM, generative AI,
    GenAI, AI exposure, AI adoption, firm value,
    information processing, informed trading, disclosure,
    analyst forecast, retail investors, hedge funds, asset management,
    peer firms, product-market peers, stock price informativeness,
    market liquidity, return predictability, financial reporting

事件：
    ChatGPT release, ChatGPT outage, Italy ban,
    DeepSeek release, ERNIE Bot release, FactSet AI launch,
    Seeking Alpha AI policy change

来源：
    SSRN, NBER, arXiv q-fin/econ, Google Scholar,
    JF, JFE, RFS, JAE, JAR, TAR, RAST, CAR, POM, MS
```

## 七、读每篇时统一记录的问题

```text
1. GenAI 在这篇里是什么？
   技术冲击 / 投资者工具 / 公司披露工具 / 分析师工具 / 研究测量工具。

2. 核心 X 是什么？
   ChatGPT release, outage, ban, AI adoption score, AI-generated text,
   investor attention, AI sentiment, GenAI announcement 等。

3. 核心 Y 是什么？
   stock returns, CAR, trading volume, liquidity, bid-ask spread,
   price informativeness, analyst forecasts, fund alpha, peer outcomes 等。

4. 识别靠什么？
   event study, DiD, outage shock, platform policy change,
   matched sample, survey validation, within-event design 等。

5. 机制是什么？
   information processing cost, limited attention, democratization,
   informed trading, analyst productivity, disclosure production,
   labor substitution, category validation, competitive risk 等。

6. 对中国 A 股/T05 的可迁移性是什么？
   数据源是否可得；X/Y 是否可复制；机制是否可写；
   是否能支撑 GenAI disclosure -> peer revaluation 的理论链条。
```
