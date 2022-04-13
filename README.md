# ColdFusion in Markdown

This VSCode extension adds better support for ColdFusion syntax in Markdown.

## Requirements

- You must install a plugin that adds language support for CFML, such as [vscode-cfml](https://github.com/KamasamaK/vscode-cfml).

## Features

- Adds CFML syntax highlighting to fenced code blocks in Markdown. This functionality is based on [this](https://github.com/mjbvz/vscode-fenced-code-block-grammar-injection-example) repository. To use, start your codeblock with `cfml` immediately after the three backticks.
- Adds CFScript syntax highlighting in fenced code blocks. Grammar is based on the one used by [vscode-cfml](https://github.com/KamasamaK/vscode-cfml). To use, start your codeblock with `cfscript` immediately after the three backticks.

## Future Additions

- Syntax highlighting in markdown preview via a markdown-it plugin. See the [VSCode documentation](https://code.visualstudio.com/api/extension-guides/markdown-extension#adding-support-for-new-syntax-with-markdownit-plugins).

## Installation

```
npm install -g vsce
vsce package --out dist
code --install-extension dist/vscode-cf-md-VERSION.vsix
```
