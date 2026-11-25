# gpui-pre (pilgrimagesoftware fork)

The published [`gpui-pre`](https://crates.io/crates/gpui-pre) and
[`gpui-pre-macos`](https://crates.io/crates/gpui-pre-macos) 0.3.7 crates,
which are a crates.io snapshot of Zed's GPUI (`zed-industries/zed` at
`f126950`). There is no upstream repository for the snapshot itself, so the
first commit on `main` imports both crates' published sources unchanged.

Branches carry small patches on top of that import, each meant to go
upstream:

- `knot/menu-alternates-0.3.7`: native alternate menu items
  (`MenuItem::alternate`, `NSMenuItem.alternate` on macOS).

Used by [Knot](https://github.com/pilgrimagesoftware/Knot-App) through
`[patch.crates-io]`. Licensed under Apache-2.0, as the crates are
(`LICENSE-APACHE` in each crate directory).
