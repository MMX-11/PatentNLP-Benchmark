# 贡献指南
欢迎参与PatentNLP-Benchmark社区建设，以下是贡献流程与规范。

## 贡献类型
1. 模型提交：上传专利领域NLP模型及评测结果
2. 数据集补充：提供高质量专利文本数据集（需标注来源与许可）
3. 代码优化：修复BUG、优化评测逻辑、扩展功能
4. 文档完善：补充使用教程、更新技术文档

## 模型提交要求
1. 提供模型基本信息：名称、任务类型（如机器翻译）、训练数据集说明
2. 附带完整评测指标：需包含对应任务的核心指标得分（如BLEU值）
3. 模型格式：支持PyTorch（.pt/.bin）、TensorFlow（.pb）格式
4. 附件：模型文件压缩包（建议小于500MB，超大型模型提供下载链接）

## PR流程
1. Fork本仓库：点击仓库页面右上角“Fork”，创建个人分支
2. 克隆个人分支：`git clone https://github.com/你的用户名/PatentNLP-Benchmark.git`
3. 创建功能分支：`git checkout -b feature/模型名称-任务类型`（如`feature/bart-translation`）
4. 提交修改：`git add .` → `git commit -m "添加XXX模型（机器翻译任务）"`
5. 推送分支：`git push origin feature/模型名称-任务类型`
6. 发起PR：GitHub个人仓库页面点击“Compare & pull request”，填写修改说明，提交审核

## Issue规范
### Bug报告
1. 标题格式：[BUG] 问题描述（如`[BUG] 模型上传后排行榜未更新`）
2. 内容包含：
   - 环境信息（系统版本、浏览器、操作步骤）
   - 错误截图或日志
   - 复现步骤

### 功能请求
1. 标题格式：[FEATURE] 功能描述（如`[FEATURE] 增加多模态模型评测功能`）
2. 内容包含：
   - 应用场景
   - 预期效果
   - 参考示例（可选）