# Template Repository: python-uv-312-devcontainer

This repository serves as a baseline template for new projects. Follow the steps below to use this template without preserving its Git history or modifying the original repository.

---

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

4. **Add and Commit Files**  
   Add all the files to the new repository:
   ```bash
   git add .
   ```
   Commit the files:
   ```bash
   git commit -m "Initial commit from template"
   ```

5. **Link to a New Remote Repository**  
   If you have created a new repository on GitHub, link it to your local repository:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-new-repo>.git
   ```
   Replace `<your-username>` and `<your-new-repo>` with the appropriate details.

6. **Push to the New Repository**  
   Push your changes to the new remote repository:
   ```bash
   git branch -M main
   git push -u origin main
   ```

---

### **Windows**
1. **Remove the Git History**  
   Open a Command Prompt or PowerShell and run:
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

4. **Add and Commit Files**  
   Add all the files to the new repository:
   ```cmd
   git add .
   ```
   Commit the files:
   ```cmd
   git commit -m "Initial commit from template"
   ```

5. **Link to a New Remote Repository**  
   If you have created a new repository on GitHub, link it to your local repository:
   ```cmd
   git remote add origin https://github.com/<your-username>/<your-new-repo>.git
   ```
   Replace `<your-username>` and `<your-new-repo>` with the appropriate details.

6. **Push to the New Repository**  
   Push your changes to the new remote repository:
   ```cmd
   git branch -M main
   git push -u origin main
   ```

---

### **macOS**
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

4. **Add and Commit Files**  
   Add all the files to the new repository:
   ```bash
   git add .
   ```
   Commit the files:
   ```bash
   git commit -m "Initial commit from template"
   ```

5. **Link to a New Remote Repository**  
   If you have created a new repository on GitHub, link it to your local repository:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-new-repo>.git
   ```
   Replace `<your-username>` and `<your-new-repo>` with the appropriate details.

6. **Push to the New Repository**  
   Push your changes to the new remote repository:
   ```bash
   git branch -M main
   git push -u origin main
   ```

---

## Notes
- This guide ensures that your new project is independent of the original repository.
- You can now customize the template to suit your project needs.

---

Happy coding!
