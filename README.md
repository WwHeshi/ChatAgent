
<div align='center'>
    <img src="https://github.com/user-attachments/assets/d5a90f6f-4fd0-4efc-9002-1f6097c906bd" alt="alt text" width="70%">
</div>

<div align="center">

<p align="center">
  <img src="https://img.shields.io/badge/python-3.12+-blue.svg?style=for-the-badge&logo=python&logoColor=white" alt="Python Version" />
  <img src="https://img.shields.io/badge/vue-3.4+-4FC08D.svg?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue Version" />
  <img src="https://img.shields.io/badge/fastapi-0.115+-009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/license-MIT-green.svg?style=for-the-badge" alt="License" />
</p>

<p align="center">
  <b>🌟 一个基于大语言模型的现代化智能对话系统 🌟</b>
</p>

<p align="center">
  支持多Agent协作 • 知识库检索 • 工具调用 • MCP服务器集成 • 实时对话
</p>


</div>

## 🎯 项目简介

AgentChat 是一个现代化的智能对话系统，基于大语言模型构建，提供了丰富的AI对话功能。系统采用前后端分离架构，支持多种AI模型、知识库检索、工具调用、MCP服务器集成等高级功能。


## ✨ 功能展示


<div align="center">

### ✨任务规划
*实时的任务流程图*
<img width="800" height="450" alt="cc59faad-4112-48cd-b9b1-6f89d3cbdb39" src="https://github.com/user-attachments/assets/53f7fe9f-d70d-4cc2-bf7e-b47a712a6d7a" />

</div>

<div align="center">


### 🔁智能体工具多轮调用

平台中智能体支持工具多轮调用
<img width="800" height="450" alt="dc426a1b220af20a06b068a4ffc2bb10" src="https://github.com/user-attachments/assets/029c70ce-e5fa-4f2c-926a-a5dfd719e237" />





</div>

---

<div align="center">

## 🛠 技术栈

### 后端技术
- **框架**: FastAPI (Python 3.12+)
- **AI集成**: LangChain, OpenAI, Anthropic
- **数据库**: MySQL 8.0, Redis 7.0
- **向量数据库**: ChromaDB, Milvus
- **搜索引擎**: Elasticsearch
- **文档处理**: PyMuPDF, Unstructured
- **异步任务**: Celery
- **部署**: Docker, Gunicorn, Uvicorn

### 前端技术
- **框架**: Vue 3.4+ (Composition API)
- **UI组件**: Element Plus
- **状态管理**: Pinia
- **路由**: Vue Router 4
- **构建工具**: Vite 5
- **开发语言**: TypeScript
- **样式**: SCSS
- **Markdown**: md-editor-v3

### 其他
- **容器化**: Docker, Docker Compose
- **反向代理**: Nginx



---



## 🚀 快速开始

</div>

<div align="center">

### 📋 系统要求

| 🛠️ **组件** | 🔢 **版本要求** | 📝 **说明** |
|:---:|:---:|:---|
| **Python** | 3.12+ | 后端运行环境 |
| **Node.js** | 18+ | 前端构建环境 |
| **MySQL** | 8.0+ | 主数据库 |
| **Redis** | 7.0+ | 缓存和会话存储 |
| **Docker** | 20.10+ | 容器化部署（推荐） |



### 🎉 **方式一：Docker一键部署（推荐）**


#### 🔥 **超简单三步部署**

</div>

```bash
# 1️⃣ 克隆项目
git clone https://github.com/Shy2593666979/AgentChat.git
cd AgentChat

# 2️⃣ 配置API密钥
cp src/backend/agentchat/config.yaml.example src/backend/agentchat/config.yaml
# 编辑配置文件，填入你的API密钥

# 3️⃣ 一键启动
cd docker
docker-compose up --build -d
```

<div align="center">

#### ✅ **验证部署**

</div>

```bash
# 查看服务状态
docker-compose ps

# 查看日志
docker-compose logs -f app
```

<div align="center">


### 🛠️ **方式二：本地开发环境**


#### 🔧 **后端环境搭建**

</div>

```bash
# 1️⃣ 克隆项目
git clone https://github.com/Shy2593666979/AgentChat.git
cd AgentChat

# 使用pip安装依赖
pip install -r requirements.txt
```
<div align="center">

#### ⚙️ **配置文件设置**

创建并编辑配置文件 `src/backend/agentchat/config.yaml`:

#### 🚀 **启动服务**

</div>

```bash
# 后端服务
cd src/backend
uvicorn agentchat.main:app --port 7860 --host 0.0.0.0

# 新终端 - 前端服务
cd src/frontend
npm install
npm run dev
```

<div align="center">

#### 🌐 **访问地址**

| 🎯 **服务** | 🔗 **地址** | 📝 **说明** |
|:---:|:---:|:---|
| **前端界面** | [localhost:8090](http://localhost:8090) | 用户界面 |
| **后端API** | [localhost:7860](http://localhost:7860) | API服务 |
| **API文档** | [localhost:7860/docs](http://localhost:7860/docs) | Swagger文档 |

</div>





---




<div align="center">

### 🌟 **我们欢迎所有形式的贡献！**

</div>


<div align="center">

本项目采用 **[MIT License](LICENSE)** 开源许可证

*这意味着你可以自由使用、修改和分发本项目 🎉*

</div>

---

<div align="center">

## 🌟 **感谢支持 AgentChat！**

*让更多的人发现这个项目，一起构建AI的未来！*


<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="
      https://api.star-history.com/svg?repos=WwHeshi/ChatAgent&type=Date&theme=dark
    "
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="
      https://api.star-history.com/svg?repos=WwHeshi/ChatAgent&type=Date
    "
  />
  <img
    alt="Star History Chart"
    src="https://api.star-history.com/svg?repos=WwHeshi/ChatAgent&type=Date"
  />
</picture>

</div>
