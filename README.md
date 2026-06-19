This repo contains a simple test case for a potential `<img>` natural dimensions (`.naturalHeight` / `.naturalWidth`) bug.

The first image has no `srcset`. The second image has a `srcset` with multiple `w` sizes, where they all point to the same exact image resource.

The values are updated at runtime with a small piece of JS, so try resizing your browser window to see if the values change.

Live site at https://sgomes.github.io/potential-img-natural-dimensions-bug/
