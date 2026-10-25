# 麦当劳MCP智能体Skill：肾友低磷配餐Agent
> 参赛：麦当劳 × 腾讯WorkBuddy 1024 MCP智能体Skill黑客松

## 项目简介
本项目是基于麦当劳MCP服务搭建的Agent Skill智能体。
针对需要控制磷摄入的人群（慢性肾病等需要低磷饮食人群），智能体根据用户预算、忌口要求，自动查询餐品磷含量，筛选低磷餐品，给出配餐推荐，同时标出高磷避雷餐品。
整个Skill在腾讯WorkBuddy平台无代码拖拽搭建，使用MCP标准化协议对接麦当劳开放接口。

## 解决痛点
需要低磷饮食的人群在外就餐选择少，很难快速查询快餐里面磷的含量，手动查营养表繁琐，不容易搭配合适套餐。
> 免责声明：本项目仅为营养数据查询参考，不构成医疗饮食建议，不能替代临床医生指导。

## 使用方式
1. 配置 MCD_MCP_TOKEN 环境变量（使用自己申请的麦当劳MCP Token），配置参考 mcp-config.example.json
2. 在 WorkBuddy 导入本Skill工程
3. 直接对话提问，示例：
> 帮我推荐50元以内低磷的麦当劳午餐，避开含奶甜品

## 演示
- 演示视频：【粘贴你的视频链接】
- 平台：腾讯 WorkBuddy
- MCP服务地址：https://mcp.mcd.cn

## 技术栈
- MCP协议（Model Context Protocol）
- 腾讯 WorkBuddy（无代码Agent搭建）
- 麦当劳开放MCP工具集
