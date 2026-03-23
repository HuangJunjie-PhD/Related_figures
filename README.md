# Related Figures - 学术论文图床

这个仓库用于存储**学术论文相关图片**，作为图床供论文翻译、学术研究和学习使用。

## 📌 仓库说明

本仓库包含多个研究领域的论文相关图片，主要用于：
- 📄 论文翻译时的图片引用
- 📚 学术研究的参考资料
- 💻 学习笔记和技术博客的配图
- 🔬 技术分享和演示材料

## 仓库结构

```
├── README.md                              # 本文件
├── ai_agents_figures/                     # AI Agents 安全论文图片（382张）
│   ├── figure-01.png                      # 知识缺口说明图
│   ├── figure-02.png                      # AI Agent 工作流程图
│   ├── figure-03.png                      # 安全威胁分类法
│   ├── figure-04.png                      # 规划威胁示意图
│   ├── figure-05.png                      # 未来研究方向
│   └── ...（共382张图片）
├── key_figures/                            # 关键图表筛选（31张大图）
├── pcie_figures/                            # PCIe 相关论文图片
│   └── ...（PCIe 规范和架构图）
├── agentee_figures/                         # 原始提取图片（382张）
├── AI_Agents_Under_Threat_完整翻译.md     # 完整中文翻译（含图表）
└── AI_Agents_Under_Threat_完整翻译_含图表.md  # 完整翻译（包含所有图片引用）
```

## 📚 存储内容

### 1. AI Agents 安全论文图片

**论文信息**：
- **标题**：AI Agents Under Threat: A Survey of Key Security Challenges and Future Pathways
- **作者**：Zehang Deng, Yongjian Guo, Changzhou Han, Wanlun Ma, Junwu Xiong, Sheng Wen, Yang Xiang
- **发表**：ACM Computing Surveys, Volume 57, Issue 7, Article 182 (July 2025)
- **DOI**：https://doi.org/10.1145/3716628
- **页数**：37 页
- **引用次数**：95（截至 2026-03-22）

**图片说明**：
- **总图片数**：382 张（从 PDF 完整提取）
- **关键图片**：
  - `figure-01.png` - AI Agent 安全知识缺口说明（4个缺口映射）
  - `figure-02.png` - AI Agent 一般工作流程（感知-大脑-行动）
  - `figure-03.png` - AI Agent 安全文献分类法（完整威胁树）
  - `figure-04.png` - 四种规划结构的规划威胁
  - `figure-05.png` - 未来研究方向
- **图片格式**：PNG 和 JPEG
- **用途**：论文翻译、学术研究、学习参考

**目录说明**：
- `ai_agents_figures/` - 所有 382 张提取图片
- `key_figures/` - 精选的 31 张关键图片（>10KB）
- `agentee_figures/` - 原始提取目录

### 2. PCIe 相关论文图片

**内容**：
- PCIe 规范和标准文档图片
- PCIe 架构示意图
- 总线和协议流程图
- 性能对比图表

**说明**：此部分图片用于 PCIe 技术研究和学习

### 3. 完整翻译文档

**文件**：
- `AI_Agents_Under_Threat_完整翻译.md` - 基础翻译版本
- `AI_Agents_Under_Threat_完整翻译_含图表.md` - 包含所有图片引用的完整版本

**内容**：
- 完整的中文翻译（约 30,000+ 字）
- 所有图表标题和说明
- 主要表格（Table 1: 威胁概览）
- 保留技术术语的英文原文

## 🔗 使用方式

### 引用图片格式

```markdown
![图片说明](https://raw.githubusercontent.com/HuangJunjie-PhD/Related_figures/main/ai_agents_figures/figure-01.png)
```

或使用关键图片：

```markdown
![图片说明](https://raw.githubusercontent.com/HuangJunjie-PhD/Related_figures/main/key_figures/figure-01.png)
```

### 示例

```markdown
如图 1 所示，AI Agent 的知识缺口包括四个主要方面：

![图 1. AI Agent 安全中知识缺口的说明](https://raw.githubusercontent.com/HuangJunjie-PhD/Related_figures/main/ai_agents_figures/figure-01.png)
```

## ⚠️ 注意事项

1. **版权声明**：所有图片仅供学术研究和个人学习使用
2. **图片来源**：图片提取自相关学术论文，版权归原作者所有
3. **引用规范**：使用时请注明原论文出处
4. **文件命名**：按照 `figure-XX.png` 格式命名，XX 为两位数字编号
5. **图床说明**：本图床专门用于学术论文相关图片的存储和引用

## 📝 更新日志

### 2026-03-23
- ✅ 添加 "AI Agents Under Threat" 论文图片（382 张）
- ✅ 提取并筛选 31 张关键图片
- ✅ 创建完整中文翻译文档（含图表）
- ✅ 更新仓库说明，标记为学术图床
- 🔄 计划完善 PCIe 相关图片索引

### 初始版本
- 初始化仓库
- 添加 PCIe 相关图片

## 📋 计划添加

- [ ] 完善 PCIe 相关图片索引和说明
- [ ] 添加更多学术论文图片
- [ ] 创建图片分类索引文件
- [ ] 添加图片尺寸和格式说明

## 📧 联系方式

如有问题或建议，请联系仓库维护者。

---

**仓库维护者**：HuangJunjie-PhD
**创建时间**：2026-03-23
**最后更新**：2026-03-23
**仓库用途**：学术论文图床（包含 PCIe 和 AI Agents 相关图片）
