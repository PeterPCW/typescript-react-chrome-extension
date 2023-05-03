# Typescript React Chrome Extension Starter

## Overview

This is meant to be a starter kit for developing a new extension in Typescript+React. It has some styling components included and types/EsLint setup so that it *should* work out of the box on current latest versions.

## Use

Install [npm](https://nodejs.org/en/download/)

Sync this repo locally (Git Bash):

```bash
git clone https://github.com/PeterPCW/typescript-react-chrome-extension
```

## Modify

Run `npm install` to build the node_modules directory. THERE WILL BE ISSUES. Always are. You can use `npm install --force` or `npm audit fix` (after a successful install) to help.

```cmd
npm install
```

Make it do whatever you want! The code here is not intended to be functional in any way.

I have real extensions in other repos that use this same setup, so you can look at them for ideas or code snippets.

Google or ChatGPT for other ideas and how-tos.

## Build and Load

Build locally (Note: this will run EsLint along the way as well):

```cmd
pnpm build
# or
npm run build
```

Then, in Chrome, go to `chrome://extensions` and click "Load unpacked" and select the `build/chrome-mv3-prod` directory.
