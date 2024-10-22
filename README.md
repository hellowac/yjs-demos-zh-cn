# Yjs Demos [![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/yjs/yjs-demos)
> 为您的创意提供起点 - 欢迎提交 PR

我们在官方网站上有更完整的 [入门指南](https://docs.yjs.dev/getting-started/a-collaborative-editor)。

* 使用 [Vertex Viewer](https://developer.vertexvis.com/) 的 3D 模型协作 - [打开演示网站](https://collaboration.vertexvis.io/)。
* 使用 [ProseMirror](http://prosemirror.net/) 编辑器的共享编辑 - [打开目录](./prosemirror/)
* 使用带版本控制支持的 [ProseMirror](http://prosemirror.net/) 编辑器进行共享编辑 - [打开目录](./prosemirror-versions/)
* 使用 [Quill](https://quilljs.com/) 编辑器的共享编辑 - [打开目录](./quill/)
* 使用 [Monaco](https://microsoft.github.io/monaco-editor/) 编辑器的共享编辑 - [打开目录](./monaco/)
* 使用 [CodeMirror](https://codemirror.net/) 编辑器的共享编辑 - [打开目录](./codemirror/)
* 使用 [CodeMirror.next](https://codemirror.net/6/) 编辑器的共享编辑 - [打开目录](./codemirror.next/)

## 入门

如果您是 Yjs 的新手，并且只想试试，请克隆此库并使用您最感兴趣的演示目录。

```sh
git clone https://github.com/yjs/yjs-demos.git
npm install
cd yjs-demos/${demo-directory}
npm install
npm start
```

演示使用公共 [`y-websocket`](https://github.com/yjs/y-websocket) 实例进行通信。尝试使用 [其他连接提供者](https://docs.yjs.dev/ecosystem/connection-provider) 或设置您自己的端点。

### (非)许可证

这些演示已发布为公有领域 - [非许可证](./LICENSE)。