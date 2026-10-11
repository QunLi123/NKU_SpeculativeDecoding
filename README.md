# NKU SpeculativeDecoding — NLP2026 Course Project (Track B: Demonstration)

团队：**创造性AI**
成员：邹博闻 (2312251) / 崔迪 (2412439)

**项目主题**：投机解码无损加速自回归大语言模型生成——原理验证、自研实现与系统评测
（Speeding Up Autoregressive LLM Generation via Speculative Decoding: Principle, Self-Implementation, and Evaluation）

## 分工
- **邹博闻（代码实现）**：自研投机解码引擎与验证循环（Phase 2），实验设计与数据分析
- **崔迪（文献与呈现）**：相关文献收集阅读、最终 ACL 报告撰写、PPT 与 Demo 演示

## 当前状态
- [x] Phase 1：Project Proposal（`proposal/Team04_Proposal.pdf`，ACL 官方模板，2 页）
- [ ] Phase 2：引擎实现 + 首个加速比（2026/10/12 → 10/31）
- [ ] Phase 3：系统实验与消融
- [ ] Phase 4：Demo + Midterm（2–3 页报告 + ≤5 页 Slides）
- [ ] Phase 5：8 页 ACL Final Report + Final Slides + Demo 视频 + 源码包

## 目录结构
```
├── proposal/                 # Phase 1：ACL 模板 + Proposal
│   ├── proposal.tex          #   源文件
│   ├── acl.sty / acl_natbib.bst / custom.bib   # ACL 官方模板
│   └── Team04_Proposal.pdf   #   Proposal（2 页）
└── README.md
```

## 仓库说明
本仓库为课程项目工作仓库；`proposal/` 使用 ACL 官方模板（`acl-org/acl-style-files`）。
后续 Phase 2 起的 `src/`、实验脚本、报告等会逐步加入。