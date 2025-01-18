# Heroicons Yew

Implementation of the Heroicons icon library for [Yew](https://yew.rs/) applications.

## Installation

Install the icons from your command line.

```shell
cargo add heroicons-yew
```

-   [View on crates.io](https://crates.io/crates/heroicons-yew)
-   [View on docs.rs](https://docs.rs/heroicons-yew/latest/heroicons_yew/)
-   [View source](https://github.com/RustForWeb/heroicons/tree/main/packages/yew)

## Usage

```rust,ignore
use heroicons_yew::Camera;
use yew::prelude::*;

#[component]
fn App() -> Html {
    html! {
        <Camera color="red" size=48 />
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
package = "heroicons-yew-book"
features = ["icons"]
files = ["src/icons.rs"]
```
