# Template Repository: UV Python 312 Devcontainer
_Fast and minimal python 3.12 VSCode devcontainer with [UV](https://docs.astral.sh/uv/) as a package mananger._  

This repository serves as a baseline template for new python projects in vscode.
Follow the steps below to use this template without preserving its Git history or modifying the original repository.

---

## Table of Contents
- [Feature Overview](#feature-overview)
- [How to Use This Template](#how-to-use-this-template)
- [Platform-Specific Instructions](#platform-specific-instructions)
  - [Linux](#linux)
  - [Windows (Command Prompt)](#windows-command-prompt)
  - [Windows (PowerShell)](#windows-powershell)
  - [macOS](#macos)
- [Notes](#notes)

---
## Feature Overview

This template provides a simple Python development setup using Dev Containers:

- **Base Image**: Uses `mcr.microsoft.com/devcontainers/python:1-3.12-bullseye` for a stable Python 3.12 environment.
- **Anonymous Volume**: Mounts `.venv` to keep virtual environment files off the local machine.
- **Post-Creation Setup**: Automatically sets permissions, installs the `uv` package, and initializes or syncs the `uv` tool.
- **VS Code Extension**: Includes `VSCode Python Extension` and `Path Intellisense` for better path suggestions.

This setup is lightweight and ready for quick Python development.

## How to Use This Template

### Step 1: Clone the Repository
Clone the repository into your desired folder. If you want to clone it into a subfolder, use the following command:

```bash
git clone https://github.com/Au2mater/python-uv-312-devcontainer.git
```

After cloning, navigate into the newly created folder:
```bash
cd python-uv-312-devcontainer
```

If you want to clone it into the current folder, use the following command instead:

```bash
git clone https://github.com/Au2mater/python-uv-312-devcontainer.git .
```

---

## Platform-Specific Instructions

### **Linux**
Run this combined command in your terminal to remove the Git history and initialize a new repository:
```bash
rm -rf .git && rm README.md && git init
```
Or follow the steps below:

1. **Remove the Git History**  
   Detach the repository from its Git history by removing the `.git` directory:
   ```bash
   rm -rf .git
   ```

2. **Remove the Existing README (Optional)**  
   If you want to replace the template's `README.md` file with your own, remove it:
   ```bash
   rm README.md
   ```

3. **Initialize a New Git Repository**  
   Set up a new Git repository for your project:
   ```bash
   git init
   ```

---

### **Windows (Command Prompt)**
Run this combined command in your Command Prompt to remove the Git history and initialize a new repository:
```cmd
rmdir .git && del README.md && git init
```
Or follow the steps below:
1. **Remove the Git History**  
   Open a Command Prompt and run:
   ```cmd
   rmdir .git
   ```

2. **Remove the Existing README (Optional)**  
   If you want to replace the template's `README.md` file with your own, run:
   ```cmd
   del README.md
   ```

3. **Initialize a New Git Repository**  
   Set up a new Git repository for your project:
   ```cmd
   git init
   ```

---

### **Windows (PowerShell)**
Run this combined command in your PowerShell to remove the Git history and initialize a new repository:
```powershell
Remove-Item -Recurse -Force .git; Remove-Item README.md; git init
```
Or follow the steps below:

1. **Remove the Git History**  
   Open PowerShell and run:
   ```powershell
   Remove-Item -Recurse -Force .git
   ```

2. **Remove the Existing README (Optional)**  
   If you want to replace the template's `README.md` file with your own, run:
   ```powershell
   Remove-Item README.md
   ```

3. **Initialize a New Git Repository**  
   Set up a new Git repository for your project:
   ```powershell
   git init
   ```

---

### **macOS**
Run this combined command in your terminal to remove the Git history and initialize a new repository:
```bash
rm -rf .git && rm README.md && git init
```
Or follow the steps below:

1. **Remove the Git History**  
   Detach the repository from its Git history by removing the `.git` directory:
   ```bash
   rm -rf .git
   ```

2. **Remove the Existing README (Optional)**  
   If you want to replace the template's `README.md` file with your own, remove it:
   ```bash
   rm README.md
   ```

3. **Initialize a New Git Repository**  
   Set up a new Git repository for your project:
   ```bash
   git init
   ```

---

## Notes
- This guide ensures that your new project is independent of the original repository.
- You can now customize the template to suit your project needs.

---

Happy coding!
