# mttydev

English · **[简体中文](./README.zh-CN.md)**

Software for working with AI agents from the terminal. Home of **miao** and **mtty** — docs for both live at [mtty.dev](https://mtty.dev).

## Projects

### [miao](https://github.com/mttydev/miao)

Your models. Your workflow. Less wasted context. An AI coding agent in a single Rust binary — TUI, desktop, iOS, and Android clients share one protocol and one session store.

```bash
curl -fsSL https://raw.githubusercontent.com/mttydev/miao/main/install | bash
```

### [mtty](https://github.com/mttydev/mtty)

An AI-native terminal and editor for local and remote work, written in Rust. See agent status per pane, get notified when input is needed, and queue your next prompt while an agent works.

### [mtty.dev](https://github.com/mttydev/mtty.dev)

Source of the [mtty.dev](https://mtty.dev) website and docs for both products.

## Internal projects

- **mtok** — LLM gateway and quota engine (private)
- **mhub** — agent hub services (private)

## Licensing

- **miao** is MIT-licensed; it is a derivative of [opencode](https://github.com/anomalyco/opencode) and keeps opencode's MIT notice.
- **mtty** is Apache-2.0.
