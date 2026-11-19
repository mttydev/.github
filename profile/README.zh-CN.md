# mttydev

[English](./README.md) · **简体中文**

从终端驾驭 AI 智能体的软件。**miao** 与 **mtty** 的家——两个产品的文档都在 [mtty.dev](https://mtty.dev)。

## 项目

### [miao](https://github.com/mttydev/miao)

你的模型，你的工作流，更少的上下文浪费。单一 Rust 二进制的 AI 编码智能体——TUI、桌面、iOS、Android 客户端共享同一协议与同一会话存储。

```bash
curl -fsSL https://raw.githubusercontent.com/mttydev/miao/main/install | bash
```

### [mtty](https://github.com/mttydev/mtty)

AI 原生终端与编辑器，Rust 编写，支持本地与远程工作。每个窗格查看智能体状态、需要输入时收到通知、智能体工作时排队下一条提示。

### [mtty.dev](https://github.com/mttydev/mtty.dev)

[mtty.dev](https://mtty.dev) 网站与文档的源码。

## 内部项目

- **mtok** — LLM 网关与配额引擎（私有）
- **mhub** — 智能体中枢服务（私有）

## 许可证

- **miao**：MIT 许可证；衍生自 [opencode](https://github.com/anomalyco/opencode)，按许可要求保留其 MIT 声明。
- **mtty**：Apache-2.0。
