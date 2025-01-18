# Heroicons Dioxus

Implementation of the Heroicons icon library for [Dioxus](https://dioxuslabs.com/) applications.

## Installation

```shell
cargo add heroicons-dioxus
```

-   [View on crates.io](https://crates.io/crates/heroicons-dioxus)
-   [View on docs.rs](https://docs.rs/heroicons-dioxus/latest/heroicons_dioxus/)
-   [View source](https://github.com/RustForWeb/heroicons/tree/main/packages/dioxus)

## Usage

```rust,ignore
use dioxus::prelude::*;
use heroicons_dioxus::Camera;

#[component]
fn App() -> Element {
    rsx! {
        Camera {
            color: "red",
            size: 48,
        }
    }
}
```

## Props

| Name                    | Type     | Default          |
| ----------------------- | -------- | ---------------- |
| `size`                  | `usize`  | `24`             |
| `color`                 | `String` | `"currentColor"` |
| `fill`                  | `String` | `"none"`         |
| `stroke_width`          | `usize`  | `2`              |
| `absolute_stroke_width` | `bool`   | `false`          |

## Icons

```toml,trunk
package = "heroicons-dioxus-book"
features = ["icons"]
files = ["src/icons.rs"]
```
