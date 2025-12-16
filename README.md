# Translate_Ollama
基于Ollama本地大模型的实时翻译网页工具
网页版左侧为实时语音识别内容，右侧为翻译，大字版，适用于小型多语言实时交流用。
html文档内容全部为deepseek输出，支持修改选其他模型
本地自行部署ollama
采用ollama本地模型来实现实时翻译，稍微有点点延迟，支持ollama- cloud模型

使用
1、下载html文档，
2、部署使用Node.js的http-serve

  **# 1. 安装Node.js（如果未安装）：https://nodejs.org/
  # 2. 安装http-server
  npm install -g http-server

  # 3. 在项目文件夹中运行
  http-server -p 8080 -c-1

3. 浏览器访问 http://localhost:8080
