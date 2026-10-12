[demo_site_model.json](https://github.com/user-attachments/files/33330004/demo_site_model.json)

---
name: examples

# Examples Skill

## Purpose

管理 DXF Site Planning Engine 的示例项目，用于展示标准工作流程、验证功能和提供开发参考。

## Responsibilities

- 提供标准 DXF 示例数据
- 展示场地规划流程
- 验证引擎处理能力
- 保存输入与输出结果
- 支持开发测试与功能验证

## Workflow

DXF Input

→ Geometry Extraction

→ Site Model

→ Planning Process

→ Validation

→ DXF Export

→ Result Review


## Example Structure

examples/

├── input/

│   ├── demo_base.dxf

│   └── site_model.json


├── output/

│   ├── result.dxf

│   └── report.json


└── README.md


## Data Requirements

- 使用统一坐标体系
- 明确文件单位
- 保持 DXF 图层结构
- 保留输入与输出记录
- 示例数据仅用于演示与测试


## Example Types

- DXF 文件读取示例
- 场地边界示例
- 建筑布局示例
- 规划校核示例
- 输出交付示例


## Validation

每个示例应包含：

- 输入数据
- 配置文件
- 处理结果
- 验证记录


## Principle

Examples provide reliable references for development, testing and demonstration.

