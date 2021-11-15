# Big Launcher

Work in progress...

## Overview

Work in progress...

## Supported platforms

- Windows (React Native 0.65)
- MacOS (React Native 0.63)
- Electron (React Native 0.65)
- Web - Next.js (React Native 0.65) (Demo only)

## Getting started

### Install

1. Clone the repository: `git clone https://github.com/josh-mcfarlin/big-launcher`
2. Run yarn install `cd big-launcher && yarn` 

### Available commands

Development and build commands:

- `yarn macos:metro`: Start the metro server for macOS
- `yarn macos:start`: Start developing the macOS app
- `yarn macos:pods`: Install macOS cocoapods dependencies
- `yarn macos:xcode`: Open the macOS app on XCode
- `yarn windows:metro`: Start the metro server for Windows
- `yarn windows:start`: Start developing the Windows app
- `yarn electron:start`: Start developing the Electron app
- `yarn electron:package:mac`: Package the production binary of the Electron app for macOS
- `yarn electron:package:win`: Package the production binary of the Electron app for windows
- `yarn electron:package:linux`: Package the production binary of the Electron app for linux
- `yarn next:start`: Start the Next.js app
- `yarn next:build`: Build the Next.js app
- `yarn next:serve`: Serve the Next.js app build

Other commands (we use [ultra-runner](https://github.com/folke/ultra-runner) to run these commands on all workspaces): 

- `yarn lint`: Lint each project
- `yarn lint:fix`: Lint + fix each project
- `yarn test`: Run tests of each project
- `yarn typecheck`: Run the TypeScript type-checking on each project
