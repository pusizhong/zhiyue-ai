# 智阅 (ZhiYue-AI) - 智能文档问答系统
项目介绍
智阅（ZhiYue-AI）是基于大模型的智能文档问答系统，支持PDF、Word、TXT文档上传，通过向量检索与AI生成技术，实现文档问答及智能摘要功能。
环境要求
- 开发工具：IntelliJ IDEA 2025.2.5
- JDK版本：Java JDK 21
- Maven：3.8+
- Docker：部署ChromaDB及项目打包
核心功能
- 📤 文档上传：支持PDF、Word（.docx）、TXT格式
- 📝 文档解析：自动解析文本并完成清洗、标准化
- 🔍 向量检索：基于ChromaDB实现文本分块、向量化及相似度检索
- 🤖 智能问答：调用智谱AI GLM-4 API，基于文档精准回答
- 📊 文档摘要：自动提取文档核心要点
- 💻 简洁界面：轻量Web交互，支持文档管理与问答
- 🚀 一键部署：Docker + docker-compose快速部署
技术栈
- 后端：Spring Boot 3（JDK 21）
- AI：智谱AI GLM-4 API
- 向量数据库：ChromaDB
- 部署：Docker
- 开发工具：IntelliJ IDEA 2025.2.5
