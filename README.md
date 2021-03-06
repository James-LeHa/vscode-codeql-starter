# vscode-codeql-starter

A starter workspace to use with the [CodeQL extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=github.vscode-codeql). For more information, see the [`vscode-codeql` repo](https://github.com/github/vscode-codeql/).

## Instructions

1. Install [Visual Studio Code](https://code.visualstudio.com).
1. Install the [CodeQL extension for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=github.vscode-codeql).
1. Clone this repository to your computer.
    - Make sure to include the submodules, either by `git clone --recursive` or by `git submodule update --init --remote` after clone.
    - Use `git submodule update --remote` regularly to keep the submodules up to date.
1. In VS Code, click File > Open Workspace. Select the file `vscode-codeql-starter.code-workspace` in your checkout of this repository.
1. You will see several folders open in the left sidebar:
    - The `ql` folder contains the [open-source CodeQL standard libraries](https://github.com/github/codeql/tree/lgtm.com) for C/C++, C#, Java, JavaScript, and Python. It tracks the `lgtm.com` branch. You can run the standard queries from here, and browse the libraries.
    - The `codeql-go` folder contains the [open-source CodeQL standard libraries](https://github.com/github/codeql-go/tree/lgtm.com) for Go. It tracks the `lgtm.com` branch. You can run the standard queries from here, and browse the libraries.
    - The folders named `codeql-custom-queries-<language>` are ready for you to start developing your own custom queries for each language, while using the standard libraries. There are some example queries to get you started.
1. Follow the [documentation for the CodeQL extension](https://help.semmle.com/codeql/codeql-for-vscode.html) to learn how to set up the extension, add a database and run queries against it. Have fun!

## Contributing

This project welcomes contributions. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## Reporting issues

Issues and suggestions should be reported in the [`vscode-codeql` repo](https://github.com/github/vscode-codeql/issues/new).

## License

This project is [licensed](LICENSE.md) under the MIT License. 

The CodeQL extension for Visual Studio Code is [licensed](https://github.com/github/vscode-codeql/blob/master/extensions/ql-vscode/LICENSE.md) under the MIT License. The version of CodeQL used by the CodeQL extension is subject to the [GitHub CodeQL Terms & Conditions](https://securitylab.github.com/tools/codeql/license).
