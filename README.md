# Chatroom Python & JavaScript

一个简单的聊天室应用，后端使用Python的FastAPI框架，前端使用JavaScript。
![JS website chat GIF](https://blog.chatengine.io/assets/per-post/nodejs-react-demo.gif)

## 功能

- 用户认证
- 跨域请求处理

### 技术栈

后端: Python, FastAPI
前端: JavaScript (具体细节未提供)

## 快速开始

以下指南将帮助你在本地机器上安装和运行项目，进行开发和测试。

### 先决条件

确保你已经安装了Python和pip。此外，你可能还需要一个适合Python开发的IDE或代码编辑器。

### 安装

1. 克隆仓库到本地机器：

```bash
git clone https://github.com/JackWang0318/chatroom-python-javascript.git
```

2. 进入项目目录：

```bash
cd chatroom-python-javascript
```

3. 安装依赖：

后端

```bash
cd backend
pip install -r requirements.txt
```

前端

```bash
cd frontend
npm install
```

4. 运行
在bakcend目录下，运行以下命令启动后端服务器：

```
python main.py
```

在frontend目录下，运行以下命令启动前端：

```
npm run dev
```