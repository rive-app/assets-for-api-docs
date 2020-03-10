# assets-for-api-docs

This repo is used to host and serve static assets referenced by Rive documenation.

Assets committed to this repo and pushed to GitHub are immediately
available for linking and reference.

## URL structure

Reference the assets with this URL structure:

`https://rive-app.github.io/assets-for-api-docs/assets/<library>/<asset>`

For example, an image named `tree.png` about `TreeView` from the
tree-widget-flutter library would go in the `assets/tree-widget-flutter/` directory and be at
`https://rive-app.github.io/assets-for-api-docs/assets/tree-widget-flutter/extra_spacing.png`.

All asset files should be under the `assets` directory in an appropriate
subdirectory.

## Shortener
We have a simple url shortener available to keep the links tidy in your source code. Replace ```https://rive-app.github.io/assets-for-api-docs/assets/``` with ```http://assets.rvcd.in/```.

### Full Length
```
https://rive-app.github.io/assets-for-api-docs/assets/tree-widget-flutter/extra_spacing.png
```
### Shortened
```
http://assets.rvcd.in/tree-widget-flutter/extra_spacing.png
```
## Credit

Inspired from Flutter's assets-for-api-docs.
