# reactjs-vscode-settings
Here I've added the vscode `settings.json` file which makes Prettier and ESLint work together for a ReactJS Project.

## Settings Overview

- `editor.defaultFormatter`: Specifies the default code formatter for VS Code, set to the Prettier extension.
- `editor.formatOnSave`: Enables automatic code formatting on save.
- `"[javascript]"` and `"[javascriptreact]"`: Disables code formatting on save specifically for JavaScript and JavaScript React (JSX) files.
- `editor.codeActionsOnSave`: Specifies that all available code actions for fixing issues should be applied explicitly on save.
- `eslint.alwaysShowStatus` and `eslint.validate`: Configures ESLint to always show its status in the editor and validate JavaScript and TypeScript files.
- `prettier.useTabs`, `prettier.jsxSingleQuote`, `prettier.tabWidth`, `prettier.arrowParens`, `prettier.singleQuote`: Customizes Prettier settings for consistent code formatting.

## Usage

To use these settings in your VS Code installation, follow these steps:

1. Clone the repository:

2. Open VS Code and navigate to settings by pressing `Ctrl + ,` or selecting `File > Preferences > Settings`.

3. Click on the `{}` icon in the top-right corner to open the settings.json file.

4. Replace the existing settings with the contents of the settings.json file from the repository.

5. Save the changes by clicking the `Save` button or pressing `Ctrl + S`.

6. Restart VS Code to apply the new settings.

