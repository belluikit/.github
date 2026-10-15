# Bellui

**Bellui** is a cross-platform UI toolkit for Go. One codebase builds apps for
desktop (macOS, Windows, Linux), mobile (iOS, Android) and the web
(WebAssembly), with Material Design 3 widgets and a WebGPU renderer. It began
as a fork of [Fyne](https://github.com/fyne-io/fyne).

- **Toolkit:** [bellui](https://github.com/belluikit/bellui)
- **Component gallery:** [gallery](https://github.com/belluikit/gallery), a showcase of every widget and theme feature
- **Website:** [bellui.com](https://bellui.com)

```sh
go get github.com/belluikit/bellui@latest
```

## Libraries behind Bellui

These are maintained for Bellui, and each can also be used on its own. Most are
forks; each repository's README credits its upstream.

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
| [clair](https://github.com/belluikit/clair) | Knowledge-base assistant for code |
| [uploader](https://github.com/belluikit/uploader) | Resumable file upload and download over gRPC |

## Also from belluikit

| Repository | What it is |
|---|---|
| [alidade](https://github.com/belluikit/alidade) | Whole-repository code graph for AI agents, served over MCP |
| [ironclad](https://github.com/belluikit/ironclad) | Encrypted, signed and licensed containers for distributing software |
| [homebrew-tap](https://github.com/belluikit/homebrew-tap) | Homebrew formulae for belluikit tools |

## Contributing

Issues and pull requests are welcome in each repository. Please read the
[Code of Conduct](https://github.com/belluikit/bellui/blob/main/CODE_OF_CONDUCT.md).
Report security issues privately through each repository's **Security** tab.
