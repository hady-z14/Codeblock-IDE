# Codeblock IDE - Open Source Ver. of VSCode by The Codeblock Team

## The Repository

This repository is where Codeblock develops the Codeblock IDE.

This source code is available to everyone under the standard [MIT license](https://github.com/microsoft/vscode/blob/main/LICENSE.txt).

## Codeblock IDE
[Codeblock IDE](https://code.visualstudio.com) is a distribution of the `VSCode` repository with Codeblock-specific customizations released under a traditional [Microsoft product license](https://code.visualstudio.com/License/).

[Codeblock IDE](https://code.visualstudio.com) combines the simplicity of a code editor with what developers need for their core edit-build-debug cycle. It provides comprehensive code editing, navigation, and understanding support along with lightweight debugging, a rich extensibility model, and lightweight integration with existing tools.

Codeblock IDE is updated monthly with new features and bug fixes. You can download it for Windows, macOS, and Linux on [Codeblock IDE Releases](https://github.com/hady-z14/Codeblock-IDE/releases/new).

## Feedback

*If You Want any help, compose a telegram message to the Codeblock channel [Telegram](https://t.me/+7UIMimMknos1MmJk)
Or tell us ideas on the Codeblock ideas channel [Telegram](https://t.me/+scMZsqWGiUwzNDRk)
## Bundled Extensions
Codeblock IDE includes built-in extensions in the [extensions](extensions) folder, including grammars and snippets for many languages. Extensions that provide rich language support (code completion, Go to Definition) for a language have the suffix `language-features`. For example, the `json` extension provides coloring for `JSON` and the `json-language-features` extension provides rich language support for `JSON`.

## Development Container

This repository includes a Visual Studio Code Dev Containers / GitHub Codespaces development container.

* For [Dev Containers](https://aka.ms/vscode-remote/download/containers), use the **Dev Containers: Clone Repository in Container Volume...** command which creates a Docker volume for better disk I/O on macOS and Windows.
  * If you already have Codeblock IDE and Docker installed, you can also click [here](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/microsoft/vscode) to get started. This will cause Codeblock IDE to install the Dev Containers extension if needed automatically, clone the source code into a container volume, and spin up a dev container for use.

* For Codespaces, install the [GitHub Codespaces](https://marketplace.visualstudio.com/items?itemName=GitHub.codespaces) extension in Codeblock IDE, and use the **Codespaces: Create New Codespace** command.

Docker / the Codespace should have at least **4 Cores and 6 GB of RAM (8 GB recommended)** to run a full build. Please take a look at the [development container README](.devcontainer/README.md) for more information.

## Code of Conduct
By The Codeblock Team

## License

Licensed under the [MIT](LICENSE.txt) license.
