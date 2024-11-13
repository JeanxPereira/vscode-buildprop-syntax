# 🛠️ Build.prop Syntax Highlighting for VS Code

![Extension Version](https://img.shields.io/badge/version-0.1.0-blue.svg)
![VS Code](https://img.shields.io/badge/VS%20Code-%3E%3D1.75.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Build](https://github.com/JeanxPereira/vscode-buildprop-syntax-buildprop-syntax/workflows/CI/badge.svg)

✨ **Build Prop Syntax Highlighting** is a Visual Studio Code extension that provides syntax highlighting for `build.prop` files commonly found in Android system images. This extension makes it easier to read and edit configuration properties by highlighting comments, keys, values, and common formatting errors.

## 📑 Features

- ✅ **Syntax Highlighting**:
  - Supports comments (`#`)
  - Highlights common property names and values
  - Detects numeric values and lists
  - Flags common formatting errors (e.g., spaces before `=`)

- 💬 **Comments Support**:
  - Easily identifies lines that start with `#`, marking them as comments for better visibility.

- 📝 **Enhanced Readability**:
  - Colors keys, values, and comments distinctly, making `build.prop` files easier to navigate.

- 🚀 **Fast and Lightweight**:
  - Minimal impact on your VS Code performance.

## 🖥️ Installation

### From the VS Code Marketplace
1. Open the **Extensions** view in VS Code (`Ctrl+Shift+X`).
2. Search for **"Build Prop Syntax Highlighting"**.
3. Click **Install**.

### Manual Installation
1. Download the `.vsix` file from the [Releases](https://github.com/JeanxPereira/vscode-buildprop-syntax-buildprop-syntax/releases) page.
2. Open a terminal and run:

   ```bash
   code --install-extension buildprop-syntax-0.1.0.vsix
   ```

## 🛠️ Usage

1. Open any `.prop` file in VS Code (e.g., `build.prop`).
2. The extension will automatically detect the file and apply syntax highlighting.
3. Enjoy improved readability and error detection!

## 🖌️ Syntax Highlighting Details

### Example

```properties
####################################
# from generate-common-build-props
####################################

ro.product.system.brand=Android
ro.product.system.device=generic
ro.system.product.cpu.abilist32=armeabi-v7a,armeabi
media.stagefright.enable-player=true
mmp.enable.3g2=true
ro.product.system.marketname=
```

### Highlighted Elements

| Element                | Example                             | Description                       |
|------------------------|-------------------------------------|-----------------------------------|
| 🔹 **Comment**         | `# This is a comment`               | Lines starting with `#`           |
| 🔸 **Property Key**    | `ro.product.system.brand=`          | Configuration keys                |
| 🟢 **Value (String)**  | `Android`, `true`                   | String values                     |
| 🟡 **Value (List)**    | `armeabi-v7a,armeabi`               | List of values separated by `,`   |
| 🔴 **Formatting Error**| `ro.product.system.cert =`          | Space before `=` detected         |

## ⚙️ Configuration

This extension works out of the box. No additional configuration is required.

## 🐞 Troubleshooting

### Common Issues
1. **No syntax highlighting applied**:
   - Make sure the file has a `.prop` extension.
   - Try restarting VS Code if the highlighting does not appear.

2. **Incorrect highlighting**:
   - Report an issue on the [GitHub repository](https://github.com/JeanxPereira/vscode-buildprop-syntax/issues) with a sample of the problematic code.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new features:

1. Fork the repository.
2. Create a new branch (`feature/your-feature`).
3. Submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- Inspired by the need for better Android development tools.
- Thanks to the open-source community for support and contributions.

## 📬 Feedback

We value your feedback! Please let us know if you encounter any issues or have feature requests by [creating an issue](https://github.com/JeanxPereira/vscode-buildprop-syntax-buildprop-syntax/issues).

---

⭐ **Enjoying the extension?** Don’t forget to give it a star on [GitHub](https://github.com/JeanxPereira/vscode-buildprop-syntax-buildprop-syntax) and leave a review in the VS Code Marketplace!
