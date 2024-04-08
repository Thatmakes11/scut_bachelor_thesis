This repository is for SCUT bachelor thesis.

## LaTeX template for SCUT thesis

### How to use:

Windows: 

- **1 => 2 => 3 => 4 => 5 (Recommended)**
- 1 => 4 => 6 (Optional)

MacOS: 

- 1 => 2 => 3 => 4 => 5

---

1. Install **LaTeX**
    - Windows:
        - Visit the [official TeX Live website](https://www.tug.org/texlive/) and download the installation package
        - Or just clip [this](https://mirror.ctan.org/systems/texlive/tlnet/install-tl-windows.exe) for installation package directly
        
    - MacOS:
        - Visit the [official MacTeX site](https://tug.org/mactex/) and download the installation package
        - Or just clip [this](https://mirror.ctan.org/systems/mac/mactex/MacTeX.pkg) for installation package directly

2. Install **VSCode**:
    - Visit the [official VSCode website](https://code.visualstudio.com/) and download the latest version for your operating system

3. Install **LaTeX Workshop** extension
    1. Open VSCode
   
    2. Press `Ctrl/Command + Shift + X` (or clip `Extensions` icon on the left sidebar)
   
    3. Type **LaTeX Workshop** in the search box
   
    4. Install LaTeX Workshop extension

4. Edit the contents as you command
    - Write your own thesis in your favorite text editor

    - Ask [LLM Chatbot](https://poe.com/TexLaTexExpert) for LaTeX instructions

5. **Compile** your LaTeX project in **VSCode**
    1. Locate your LaTeX project folder in VSCode and open the main tex file (**main.tex**)
   
    2. Compile in VSCode
        -  Press `Ctrl/Command + Alt + B` to compile the tex file instantly
        - Or use the command palette `Ctrl/Command + Shift + P`, type **latex workshop: Build LaTeX project**, and hit `Enter` 
        - Or clip the `TEX` icon on the left sidebar, then choose **Build LaTeX project**

6. **Compile** your LaTeX project in **TeXworks**
    > TeXworks is with TeX Live

    1. Open TeXworks and locate your main tex file (`main.tex`) in TeXworks
    
    2. Complie your project using this ***magical*** sequence: 
        - XeLaTeX => Biber => XeLaTeX => XeLaTeX

---

There you have it, happy LaTeXing.
