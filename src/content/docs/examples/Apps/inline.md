---
title: Inline Viewport
---

Demonstrates the
[`Inline`](https://docs.rs/ratatui/latest/ratatui/enum.Viewport.html#variant.Inline) Viewport.

```shell title=run example
git clone https://github.com/ratatui/ratatui.git --branch latest
cd ratatui
cargo run --example=inline --features=crossterm
```

![inline](inline.gif)

```rust title=inline.rs
{{ #include @code/examples/ratatui-examples/examples/inline.rs }}
```
