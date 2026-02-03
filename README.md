# Installation
This project uses a non-standard python libary (pyautogui) and its dependencies.

- Pre-requisite: Install the most recent download of Python at https://www.python.org/downloads/
  - Alternatively, you can use a package manager such as winget `winget install python`.
1. Clone the repository into a directory of your choice.
2. Navigate to the directory in your terminal.
3. In the terminal window, Run `python -m venv venv` to create a virtual environment named "venv".
4. Activate the virtual environment by using the venv activate script which corresponds to your shell:  
  Windows PowerShell:  
  `venv\Scripts\Activate.ps1`  
  Windows Command Prompt:  
  `venv\Scripts\activate.bat`
6. Run `pip install -r requirements.txt`, this will install the project's dependencies into your virtual environment.

# Run the program
1. Open the cloned directory in your terminal or IDE.
2. Activate the virtual environment.
3. Run the program with `python app.py` or your IDE's built-in code runner.
