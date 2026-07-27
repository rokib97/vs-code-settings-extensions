# vs-code-settings-extensions

A curated collection of Visual Studio Code configurations and extension settings optimized for a modern full-stack development workflow, with a heavy focus on JavaScript, TypeScript, React, and C++.

## 🚀 Features

- **Web Development**: Deep integration for Tailwind CSS, React (JSX), and HTML/CSS.
- **Code Quality**: Automated formatting on save using Prettier and linting via ESLint.
- **Multi-Language Support**: Extensive `code-runner` configurations for quickly executing scripts in C, C++, Java, Python, Rust, Go, and many more.
- **UI/UX Enhancements**: 
    - Custom font support (Dank Mono).
    - High-visibility terminal settings.
    - Specialized theme and icon configurations.
    - Error Lens integration for inline diagnostic warnings.
- **Productivity**: Path autocomplete, automatic import organization, and linked editing.

## 🛠️ Recommended Extensions

Based on the `setting.json`, the following extensions are required or highly recommended to get the most out of these settings:

- **Formatting & Linting**: 
    - `esbenp.prettier-vscode` (Prettier)
    - `dbaeumer.vscode-eslint` (ESLint)
- **Language Support**:
    - `tailwindCSS.tailwindCSS` (Tailwind CSS IntelliSense)
    - `ms-vscode.cpptools` (C/C++ Extension Pack)
- **Utility**:
    - `formulahendrix.code-runner` (Code Runner)
    - `usernamehw.errorlens` (Error Lens)
    - `christian-kohler.path-autocomplete` (Path Autocomplete)
    - `ritwickgo.LiveServer` (Live Server)
    - `peakingduck.peacock` (Peacock)

## ⚙️ Installation

To apply these settings to your own VS Code installation:

1. Open Visual Studio Code.
2. Open your `settings.json` file:
   - **Windows/Linux**: `File` > `Preferences` > `Settings` > Click the **Open Settings (JSON)** icon in the top right.
   - **macOS**: `Code` > `Settings` > `Settings` > Click the **Open Settings (JSON)** icon in the top right.
3. Copy the contents of the `setting.json` file from this repository.
4. Paste them into your `settings.json` file, merging them with your existing configurations if necessary.

## 📝 Notes

- **Fonts**: These settings specify `Dank Mono`. If you do not have this font installed, please update the `editor.fontFamily` field to a font available on your system (e.g., `'Fira Code'`, `'Cascadia Code'`, or `'JetBrains Mono'`).
- **C++ Execution**: The C compiler configuration is currently set to use `input.txt` and `output.txt` for input/output redirection. Modify the `code-runner.executorMap` for `"c"` if you prefer standard console I/O.
