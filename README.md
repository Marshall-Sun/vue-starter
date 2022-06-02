## 安装依赖

1. 安装 Node.js 环境，[下载链接](http://nodejs.cn/download/)

2. 打开一个终端，比如 CMD / Powershell 等，输入以下代码来查看安装好的 Node.js 版本号：

    ```sh
    node -v
    ```

    请确保 Node.js 版本大于 14.17.6，越新越好。

3. 在终端中**定位到本文件夹下**，后续操作都要在本文件夹下进行。

4. 分别输入以下代码以安装项目依赖：

    ```sh
    npm config set registry https://registry.npmmirror.com
    npm install
    ```

## 预览项目

在终端中**定位到本文件夹下**，输入以下代码以预览项目：

```sh
npm run dev
```

当项目运行后，访问 http://localhost:3333 即可。
