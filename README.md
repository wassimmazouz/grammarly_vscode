# Grammarly Extension for VSCode (Discontinued)

This repository contains the discontinued Grammarly extension for Visual Studio Code. Although Grammarly no longer officially supports this extension, you can still use it by manually installing the provided `.vsix` file.

## Installation Guide

You can install the Grammarly extension manually either through the VSCode interface or using the command line.

### Method 1: Install via VSCode Interface

1. Download the `.vsix` file from this repository.
2. Open Visual Studio Code.
3. Navigate to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Ctrl+Shift+X`.
4. Click on the three-dot menu (`...`) at the top-right corner of the Extensions view.
5. Select `Install from VSIX...`.
6. Browse to the location where you downloaded the `.vsix` file and select it.
7. The extension will be installed, and you may need to reload VSCode for the changes to take effect.

### Method 2: Install via the Command Line

1. Download the `.vsix` file from this repository.
2. Open your terminal or command prompt.
3. Navigate to the directory where the `.vsix` file is located.
4. Run the following command to install the extension:
    ```bash
    code --install-extension grammarly.vsix
    ```

5. The extension will be installed, and you may need to reload VSCode for the changes to take effect.
If the previous instructions are not sufficient, you have to ensure that the Grammarly Language Server can be initialized correctly, please follow the instructions below:

Create the necessary directory with appropriate permissions.
Open your terminal and run the following commands:
```bash
sudo mkdir -p ~/.config/grammarly-languageserver/
chmod -R u+w ~/.config
sudo chmod 777 ~/.config/grammarly-languageserver/
```

## Note

As this is a discontinued extension, some features might not work as expected with the latest versions of Visual Studio Code. Use it at your own discretion.

## License

This project is licensed under the MIT License.s
## Acknowledgments

Thanks to the original developers of the [Grammarly extension for Visual Studio Code](https://github.com/znck/grammarly)

Thanks also to [Artim436](https://github.com/Artim436) for contributing to making this extension work.
 

