# PatentNLP-Benchmark
专利领域大模型评测基准与开源社区，提供模型评测、数据集共享、技术交流功能。

## 核心功能
- 📊 评测基准：覆盖机器翻译、自动摘要、知识抽取等6大专利NLP任务
- 📤 资源共享：模型/数据集上传下载，支持版本管理
- 📈 实时排行：按BLEU、ROUGE、MRR等指标动态排序
- 💬 社区交流：GitHub Discussions与Issues双渠道互动

## 快速开始
1. 访问Benchmark系统：[https://你的域名]（部署后补充）
2. 查看评测结果：./docs/evaluation_results.md
3. 贡献指南：查看CONTRIBUTING.md

## 评测指标
| 任务类型       | 核心指标                  |
|----------------|---------------------------|
| 机器翻译       | BLEU、ROUGE-1/2/L         |
| 自动摘要       | BLEU、ROUGE-1/2/L         |
| 知识抽取       | AUC、Macro-F1             |
| 知识表示       | MRR、Hits@K               |
| 语义匹配       | Mean、Median、StdDev      |
| 多模态         | CLIP、TIFA                |

## 资源链接
- 数据集获取：./datasets/README.md
- 预训练模型：./models/README.md
- 技术文档：./docs/
- 社区讨论：https://github.com/openKG-field/PatentNLP-Benchmark/discussions