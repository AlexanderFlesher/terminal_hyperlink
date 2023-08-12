## terminal-hyperlink

This crate uses a trait to style terminal text with the escape code for url hyperlinks.

```rust
use terminal_hyperlink::Hyperlink;

fn main() {
  println!("{}", "Hello World!".hyperlink("https://github.com/AlexanderFlesher/terminal_hyperlink"));
}
```

To detect whether your terminal supports hyperlinks, you should use the
[supports-hyperlinks](https://crates.io/crates/supports-hyperlinks) crate.
