Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML``   # Metahelper AI - DeepSeek Style Chat Interface  A beautiful, lightweight AI chat application featuring a DeepSeek-inspired interface with dark/light theme support. Powered by GPT4All's local language models for complete privacy and offline functionality.  ![Metahelper AI Demo](test.gif)  ## ✨ Features  - **DeepSeek-Inspired UI** - Clean, modern chat interface with message bubbles  - **Dark/Light Theme Toggle** - Switch between eye-friendly themes  - **Real-time Streaming** - See responses generate token by token  - **Local Processing** - 100% private, runs entirely on your machine  - **Portable Setup** - Includes all dependencies in `_portable` directory  - **Responsive Design** - Auto-scrolling with proper message formatting  - **Keyboard Shortcuts** - Send with Enter, new line with Shift+Enter  - **No Console Window** - Runs as a proper GUI application (`.pyw`)  ## 🚀 Quick Start  ### Prerequisites  - Python 3.8 or higher  - 4GB+ RAM recommended  ### Installation  1. **Download the latest release**     Download the latest portable package from the [releases page](https://github.com/ThatBoyLight714/SchoolProjectAI/releases), or clone the repository:     ```bash     git clone https://github.com/ThatBoyLight714/SchoolProjectAI.git     cd SchoolProjectAI   ``

1.  Download a compatible GGUF model and place it in the models folder:textSchoolProjectAI/├── models/│ └── orca-mini-3b-gguf2-q4\_0.gguf├── \_portable/├── app.pyw└── test.gif_Recommended model:_ [_orca-mini-3b-gguf2-q4\_0.gguf_](https://huggingface.co/TheBloke/orca_mini_3B-GGUF)
    
2.  Double-click app.pyw (no console window appears) or run:bashpython app.pyw
    

🎨 Theme Support
----------------

Toggle between light and dark mode with the theme button in the header:

Light ModeDark ModeClean, professional appearanceEasy on the eyes for night use

📦 Portable Package
-------------------

The release includes a \_portable directory containing:

*   PyQt6 libraries
    
*   GPT4All with pre-built DLLs
    
*   All necessary dependencies
    

No system-wide installation required!

🛠️ Configuration
-----------------

You can modify the model parameters in app.pyw:

python

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   # Generation settings  max_tokens=512  temp=0.7  top_k=40  top_p=0.9  repeat_penalty=1.1   `

📁 Project Structure
--------------------

text

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   SchoolProjectAI/  ├── app.pyw                 # Main application (no console)  ├── models/                 # Place GGUF models here  │   └── your-model.gguf  ├── _portable/              # Portable dependencies  │   ├── PyQt6/  │   └── gpt4all/  ├── test.gif                # Demo animation  └── README.md   `

🔧 Troubleshooting
------------------

**Model not found error**

*   Ensure your model is in the models folder
    
*   Check that the filename matches in the script (default: orca-mini-3b-gguf2-q4\_0.gguf)
    

**DLL load issues**

*   The portable package includes all required DLLs
    
*   If issues persist, install gpt4all locally: pip install gpt4all
    

**Application closes immediately**

*   Run from terminal to see error messages: python app.pyw
    
*   Check that all dependencies are present in \_portable
    

**Portable dependencies not found**

*   Make sure the \_portable folder is in the same directory as app.pyw
    
*   Do not modify the contents of \_portable
    

🖥️ Running Without Console
---------------------------

The .pyw extension ensures the application runs without a terminal window:

*   **Windows**: Double-click app.pyw to launch directly
    
*   **Linux/Mac**: Use pythonw app.pyw if available, or standard python app.pyw
    

📥 Downloads
------------

Get the latest version from the [releases page](https://github.com/ThatBoyLight714/SchoolProjectAI/releases):

*   **Source code** (zip)
    
*   **Source code** (tar.gz)
    
*   **Portable package** (coming soon)
    

🤝 Contributing
---------------

Contributions are welcome! Feel free to:

*   Report bugs via [Issues](https://github.com/ThatBoyLight714/SchoolProjectAI/issues)
    
*   Suggest features
    
*   Submit pull requests
    

📝 License
----------

MIT License - feel free to use and modify for your own projects.

🙏 Credits
----------

*   Built with [PyQt6](https://www.riverbankcomputing.com/software/pyqt/)
    
*   Powered by [GPT4All](https://gpt4all.io/)
    
*   UI inspired by [DeepSeek](https://deepseek.com/)
    
*   Created by Divine Asiegbu
    

**Note**: First run may take a few seconds to load the model. Subsequent responses will be faster!

🐛 Known Issues
---------------

*   Initial model loading may take 10-30 seconds depending on your system
    
*   Some models may require specific GGUF formats
    
*   RAM usage varies by model size (3B models use ~2-4GB)
    

📊 System Requirements
----------------------

ComponentMinimumRecommendedRAM4GB8GB+Storage2GB5GB+Python3.83.11+OSWindows 10Windows 11 / Linux / macOS

_Made with ❤️ for school project_

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   This MD file includes:  - Correct GitHub repository links  - Proper formatting for GitHub markdown  - Tables for better organization  - Clear sections for troubleshooting  - System requirements table  - Known issues section  - Proper credit and licensing information   `
