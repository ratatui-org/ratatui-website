---
title: Tabs
---

Demonstrates the [`Tabs`](https://docs.rs/ratatui/latest/ratatui/widgets/struct.Tabs.html) widget.

```shell title=run example
git clone https://github.com/ratatui/ratatui.git --branch latest
cd ratatui
cargo run --example=tabs --features=crossterm
```

![tabs](tabs.gif)

```rust title=tabs.rs
{{ #include @code/examples/ratatui-examples/examples/tabs.rs }}
```
