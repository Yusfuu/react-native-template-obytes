---
sidebar_position: 1
---

# Create a new app

Let's create a new React native project with obytes starter.

## Requirements

First make sure you have the following tools installed on your machine:

- [React Native dev environment ](https://reactnative.dev/docs/environment-setup)
- [Node.js LTS release](https://nodejs.org/en/)
- [Git](https://git-scm.com/)
- [Watchman](https://facebook.github.io/watchman/docs/install#buildinstall), required only for macOS or Linux users
- [Yarn](https://classic.yarnpkg.com/en/docs/install)
- [Expo Cli](https://docs.expo.dev/workflow/expo-cli/)
- [VS Code Editor](https://code.visualstudio.com/download)

## Initializing a new project

Start your project using `create-obytes-app` command:

```bash
npx create-obytes-app@latest MyApp
```

The command will create an expo app named `MyApp` and install all the dependencies added by the starter.

:::note
Because we're using the Expo custom dev client to support native dependencies with the starter. The Expo Go app is not an option to consider here; instead, you need to create the app and install it on your simulator or device to start using it.
:::

## Open Project on VS Code

VS code is the recommended editor for this starter, The starter comes with a list of recommended extensions,settings and project snippets that we think will improve your coding experience.

Open the project on VS Code using the following command:

```bash
code .
```

When you open the project on VS Code you will see a popup asking you to install the recommended extensions, the easy way is to install all recommended extensions by clicking on `Install All` button.

To ensure that your code is properly validated and formatted, we highly recommend installing all of the recommended extensions. However, if you're hesitant to install them all, we suggest at least installing the following extensions, as they are essential to our code validation and formatting on file save:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Tailwindcss IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

Here is the complete list of recommended extensions:

- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [tailwindcss IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Auto close tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Code spell checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [Cobalt 2 theme](https://marketplace.visualstudio.com/items?itemName=ahmadawais.theme-cobalt2)
- [Turbo console log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)
- [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokallise.i18n-ally)
- [Github copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

## Running the app

If the installation was successful, the created app should be ready to use, and because we are using the expo custom dev client, you may launch the app on your simulator or device by running the following command:

```bash
# Run the app on iOS simulator
yarn ios

# Run the app on Android simulator
yarn android
```
