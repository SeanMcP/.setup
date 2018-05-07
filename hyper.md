# Hyper

I prefer Hyper because of its cross-platform support; it is available on MacOS, Windows, and Linux. Also, installing new plugins is easy from the command line.

## Plugins

Name | Reason
--- | ---
hyper-statusline | Displays git info in status bar
hypercwd | Opens new tab in current working directory
hyper-search | Additional search features

### Install

Open `.hyper.js` and edit the `plugins` array.

```javascript
plugins: ["hyper-statusline", "hypercwd", "hyper-search", "nord-hyper"],
```

### Command line

Use `$ hyper i name-of-plugin` to quickly add plugin.
