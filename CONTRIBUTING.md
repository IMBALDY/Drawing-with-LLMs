# Drawing with LLMs 项目协作指南

欢迎参与 Drawing with LLMs 项目的开发！这个文档将指导您如何参与项目协作。

## 目录

- [开始之前](#开始之前)
- [开发流程](#开发流程)
- [分支管理](#分支管理)
- [提交规范](#提交规范)
- [代码审查](#代码审查)
- [项目结构](#项目结构)

## 开始之前

1. 确保你已经有了 GitHub 账号
2. 接受项目协作邀请（检查您的邮箱）
3. 安装必要的开发工具：
   - Git
   - Python 3.8+
   - 您喜欢的代码编辑器（推荐 VS Code）

## 开发流程

1. 克隆仓库到本地：
```bash
git clone https://github.com/IMBALDY/Drawing-with-LLMs.git
cd Drawing-with-LLMs
```

2. 创建并切换到新的功能分支：
```bash
git checkout -b feature/your-feature-name
```

3. 进行开发和测试

4. 提交您的更改：
```bash
git add .
git commit -m "feat: 添加新功能描述"
```

5. 推送到远程仓库：
```bash
git push origin feature/your-feature-name
```

6. 创建 Pull Request（PR）

## 分支管理

- `main`: 主分支，用于发布
- `feature/*`: 功能分支，用于开发新功能
- `bugfix/*`: 修复分支，用于修复 bug
- `docs/*`: 文档分支，用于更新文档

## 提交规范

提交信息格式：
```
<type>: <subject>

[optional body]
```

类型（type）：
- `feat`: 新功能
- `fix`: 修复 bug
- `docs`: 文档更改
- `style`: 代码格式调整
- `refactor`: 代码重构
- `test`: 测试相关
- `chore`: 构建过程或辅助工具的变动

示例：
```
feat: 添加图形生成功能

- 实现基本的 SVG 生成
- 添加颜色处理
- 优化渲染性能
```

## 代码审查

1. PR 提交后，请等待维护者审查
2. 如有需要修改的地方，请及时更新
3. 所有 CI 测试通过后才能合并

## 项目结构

```
drawing-with-llms/
├── src/                # 源代码目录
├── kaggle_evaluation/  # Kaggle 评估相关代码
├── tests/             # 测试文件
├── docs/              # 文档
└── README.md          # 项目说明
```

## 开发建议

1. 在开始新功能开发前，请先创建 Issue 讨论
2. 保持代码风格一致
3. 编写必要的测试用例
4. 及时更新文档

## 联系方式

如有任何问题，请：
1. 创建 Issue
2. 在 PR 中讨论
3. 通过邮件联系维护者

感谢您的贡献！ 