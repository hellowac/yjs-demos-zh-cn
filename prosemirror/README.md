# ProseMirror Demo
> [y-prosemirror](https://docs.yjs.dev/ecosystem/editor-bindings/prosemirror) / [y-websocket](https://docs.yjs.dev/ecosystem/connection-provider/y-websocket) / [实时演示](https://demos.yjs.dev/prosemirror/prosemirror.html)

这是一个使用 Yjs 和 y-prosemirror 使 [ProseMirror](https://prosemirror.net/) 编辑器协作的演示。该演示使用 [prosemirror-example-setup](https://github.com/ProseMirror/prosemirror-example-setup) 作为配置。了解更多关于如何使用 ProseMirror 构建您自己的自定义编辑器的信息，请查看 [他们的文档](https://github.com/yjs/y-prosemirror/)。

我们使用 [y-websocket](https://docs.yjs.dev/ecosystem/connection-provider/y-websocket) 提供程序通过服务器共享文档更新。Yjs 还有许多其他可用的提供程序 - 尝试切换到另一个提供程序。[查看文档](https://docs.yjs.dev/ecosystem/connection-provider)。

您还可以尝试为此演示添加离线持久性。如果文档更新在浏览器中持久化，那么加载您的应用程序会更快，这不是很酷吗？试试吧：https://docs.yjs.dev/getting-started/allowing-offline-editing

## 快速开始

```sh
npm i
npm start
# 项目正在运行在 http://localhost:8080/
```