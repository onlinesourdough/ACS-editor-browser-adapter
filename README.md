# ACS Editor Browser Adapter

Online Sourdough's working fork of
[Diffusion Studio](https://github.com/diffusionstudio/editor), an open-source
video editor that agents can operate through code and a command-line interface.

This repository contains the editor source. For the official app and maintained
installation instructions, use [diffusion.studio](https://diffusion.studio).
AIOS's [Diffusion Studio skill](https://github.com/onlinesourdough/AIOS-Plugin/tree/main/skills/diffusion-studio)
documents the selected external editor workflow.

## Development

Requirements: Node.js 20+ and npm. Clone this fork, install the workspace
dependencies and create the required local configuration:

```sh
git clone https://github.com/onlinesourdough/ACS-editor-browser-adapter.git
cd ACS-editor-browser-adapter
npm ci
cp apps/web/.env.example apps/web/.env
npm run dev
```

The default development command starts the desktop application. It does not
install AIOS or connect an agent automatically.

## Documentation and attribution

- [Editor capabilities, examples and contribution guide](docs/upstream-editor.md)
- [CLI reference](reference/README.md)
- [Composition reference](reference/jsx/README.md)
- [Examples](examples/README.md)

Diffusion Studio is created by Diffusion Studio Inc. The source retains its
[MPL-2.0 license](LICENSE). Its brand assets retain their original rights.
