
# Description

This is a basic template for creating Electron applications with Vite, Vue, and TypeScript. It utilizes the integrated development tool `electron-forge` to simplify the development process, making it similar to using traditional cli. 

# Tech Stack

List the technologies and tools used in your project.

- Electron
- Vue
- Vite
- TypeScript

# Getting Started
### Install the dependencies:

```shell
yarn
```
### Run the project in development mode:
```shell
yarn start
```
### Build the project for production:
```shell
yarn package
```

### Clone the Repository:
```shell
git clone https://github.com/hesoso/electron-vue-vite-ts.git
```

# Directory Structure
### The directory structure of this project is as follows:

```
electron-vue/
├── app/                      # Electron code
│   ├── main.ts               # Electron main process files
│   ├── preload.ts            # Preload scripts
│   └── renderer.ts           # Vue renderer process files
├── web/                      # Vue code
├── out/                      # Electron bundle files
├── forge.config.ts           # Forge configuration file
├── vite.main.config.ts       # Main configuration file
├── vite.preload.config.ts    # Preload configuration file
├── vite.renderer.config.ts   # Renderer configuration file
└── package.json              # Project dependencies and scripts
```
