# Heroicons Leptos

Implementation of the Heroicons icon library for [Leptos](https://leptos.dev/) applications.

## Installation

Install the icons from your command line.

```shell
cargo add heroicons-leptos
```

-   [View on crates.io](https://crates.io/crates/heroicons-leptos)
-   [View on docs.rs](https://docs.rs/heroicons-leptos/latest/heroicons_leptos/)
-   [View source](https://github.com/RustForWeb/heroicons/tree/main/packages/leptos)

## Usage

```rust,ignore
use leptos::prelude::*;
use heroicons_leptos::Camera;

#[component]
fn App() -> impl IntoView {
    view! {
        <Camera color="red" size=48 />
    }
}
```

## Props

| Name                    | Type             | Default          |
| ----------------------- | ---------------- | ---------------- |
| `size`                  | `Signal<usize>`  | `24`             |
| `color`                 | `Signal<String>` | `"currentColor"` |
| `fill`                  | `Signal<String>` | `"none"`         |
| `stroke_width`          | `Signal<usize>`  | `2`              |
| `absolute_stroke_width` | `Signal<bool>`   | `false`          |

## Icons

```toml,trunk
package = "heroicons-leptos-book"
features = ["icons"]
files = ["src/icons.rs"]
```
