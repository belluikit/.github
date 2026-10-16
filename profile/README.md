<p align="center">
  <a href="https://bellui.com"><img src="https://bellui.com/images/logo-256.webp" alt="Bellui" width="128" height="128"></a>
</p>

<h1 align="center">Bellui</h1>

<p align="center">
  Native apps in Go, on every screen.<br>
  <a href="https://bellui.com">bellui.com</a> ·
  <a href="https://bellui.com/develop/">Get started</a> ·
  <a href="https://bellui.com/docs/">Docs</a> ·
  <a href="https://bellui.com/extensions/">Extensions</a>
</p>

**Bellui** is a UI toolkit for Go with Material Design 3 widgets and WebGPU
rendering. One codebase builds apps for macOS, Windows, Linux, Android, iOS
and the browser (WebAssembly). It began as a fork of
[Fyne](https://github.com/fyne-io/fyne).

```sh
go get github.com/belluikit/bellui@latest
```

- **Toolkit:** [bellui](https://github.com/belluikit/bellui), including the
  extension modules for [charts](https://bellui.com/extensions/charts/),
  [data tables](https://bellui.com/extensions/tables/), a
  [code editor](https://bellui.com/extensions/editor/),
  [graphs](https://bellui.com/extensions/dag/) and
  [media](https://bellui.com/extensions/mmedia/)
- **Gallery:** every widget, theme and extension in one app,
  [toured on the website](https://bellui.com/gallery/)

## Libraries behind Bellui

Maintained for Bellui, and each usable on its own. Most are forks; each
repository's README credits its upstream.

| Repository | What it is |
|---|---|
| [webgpu](https://github.com/belluikit/webgpu) | Go bindings for wgpu-native (WebGPU) on desktop, mobile and the browser |
| [glfw](https://github.com/belluikit/glfw) | Go bindings for GLFW 3.4, with Wayland drag-and-drop, touch and IME extensions |
| [glfw-js](https://github.com/belluikit/glfw-js) | GLFW-style windowing for Go on desktop and in the browser |
| [gl-js](https://github.com/belluikit/gl-js) | Go bindings for OpenGL, OpenGL ES and WebGL |
| [typesetting](https://github.com/belluikit/typesetting) | Text shaping and typesetting in pure Go |
| [systray](https://github.com/belluikit/systray) | System tray icons and menus |
| [fsnotify](https://github.com/belluikit/fsnotify) | Cross-platform filesystem notifications |
| [gocef](https://github.com/belluikit/gocef) · [gocef-libs](https://github.com/belluikit/gocef-libs) | Chromium Embedded Framework bindings for the Linux web view, and its pinned runtime |
| [goffmpeg](https://github.com/belluikit/goffmpeg) · [goffmpeg-libs](https://github.com/belluikit/goffmpeg-libs) | FFmpeg bindings and prebuilt LGPL libraries for media playback and capture |

## Tools

| Repository | What it is |
|---|---|
| [**Alidade**](https://github.com/belluikit/alidade) | A map of your whole repository for AI coding agents, served over MCP: who calls what, built by the compilers ([more](https://bellui.com/tools/alidade/)) |
| [Clair](https://github.com/belluikit/clair) | A searchable index of a Go framework's API and your own project ([more](https://bellui.com/tools/clair/)) |
| [Uploader](https://github.com/belluikit/uploader) | Resumable file upload and download over gRPC, with a Go SDK ([more](https://bellui.com/tools/uploader/)) |
| [ironclad](https://github.com/belluikit/ironclad) | Encrypted, signed and licensed containers for distributing software |
| [homebrew-tap](https://github.com/belluikit/homebrew-tap) | Homebrew formulae for belluikit tools |

## Contributing

Issues and pull requests are welcome in each repository; see
[Support](https://bellui.com/support/) for where things go. Please read the
[Code of Conduct](https://github.com/belluikit/bellui/blob/main/CODE_OF_CONDUCT.md).
Report security problems privately to
[bellui@trendvidia.com](mailto:bellui@trendvidia.com), not in public issues.
