# Drawing with LLMs

Kaggle评估系统集成工具，用于生成符合Kaggle规范的可视化SVG并通过gRPC协议提交评估。

## 功能特性
- SVG规范验证与自动修复
- gRPC双向流通信支持
- 评估结果可视化报告生成

## 安装指南
```bash
pip install -r requirements.txt
python -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. kaggle_evaluation/core/kaggle_evaluation.proto
```

## 使用示例
```python
from kaggle_evaluation.svg_gateway import SVGGateway

gateway = SVGGateway()
gateway.submit_drawing(svg_content="<svg>...</svg>")  # 提交SVG内容
evaluation_result = gateway.get_evaluation()  # 获取评估结果
```

## 贡献指南
1. 克隆仓库并创建特性分支
2. 修改代码后运行测试：`pytest tests/`
3. 提交包含完整测试覆盖的Pull Request

## 许可证
MIT License