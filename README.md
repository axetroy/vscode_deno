> Fork from [justjavac/vscode-deno](https://github.com/justjavac/vscode-deno)
>
> Thanks for his contribution

# VS Code Deno extension

[![Version](https://vsmarketplacebadge.apphb.com/version/axetroy.vscode-deno.svg)](https://marketplace.visualstudio.com/items?itemName=axetroy.vscode-deno)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads/axetroy.vscode-deno.svg)](https://marketplace.visualstudio.com/items?itemName=axetroy.vscode-deno)

Adds Deno support for VS Code using the [TypeScript Deno language service plugin](typescript-deno-plugin).

## Usage

This extension works using VS Code's **built-in version** of TypeScript. You do not need to configure the plugin in your `tsconfig.json` if you are using VS Code's version of TypeScript.

If you are using VS Code 1.30 or older and are [using a **workspace version** of typescript](https://code.visualstudio.com/Docs/languages/typescript#_using-newer-typescript-versions), you must currently configure the TS Server plugin manually by following [these instructions](https://github.com/justjavac/typescript-deno-plugin#configuration)

## Configuration

- `deno.enabled` - Enable/disable this extension. Default is `true`.

- `deno.alwaysShowStatus` - Always show the Deno status bar item. Default is `true`.

## Commands

This extension contributes the following commands to the Command palette.

- `Enable Deno` - Enable this extension.
- `Disable Deno` - Disable this extension.

## Contribute

Report a bug or a suggestion by posting an issue on the [git repository](https://github.com/axetroy/vscode-deno).
