# Competitions App

This a competition app that reads data from a csv and then data is imported and saved into a MySQL database, with the competition name/id used to link to the imported data, the program then asks how many winners are needed and randomly selects the winners from csv records, displaying the results in the console. The results are saved in the database and output to a text file that includes competition details, winners, and contact information. Finally, auditing is added to track all procedures

[![asciicast](https://asciinema.org/a/P4RBJlEUdZ3UeMqgp1joEdSk5.svg)](https://asciinema.org/a/P4RBJlEUdZ3UeMqgp1joEdSk5)

## Installation

1. Requirement before running the app:

    • Make sure a Python Interpreter is installed on the    Host Machine

    • Install MySQL with MySQL Installer for Windows OS

    Configure the connection to the database using environment variables for the password and database name in python application.py code 

    TIPS: For setting environment variables on Windows Operting System
    https://www.youtube.com/watch?v=NDbr32xMUDQ&list=WL&index=2&t=74s

    Create a database named testdb on mysql

    [![asciicast](https://asciinema.org/a/4uLsIrbIwSVi9wJ6tp9Zpox7k.svg)](https://asciinema.org/a/4uLsIrbIwSVi9wJ6tp9Zpox7k)

2. Excecute the batch file run_myscript.bat to run the application to skip below steps for Windows only.

2. Install virtualenv via pip on the Host Machine

    ```bash
    python -m pip install --user virtualenv
    python -m virtualenv –help
    ```

    Create a virtual environment folder in the project directory
    ```bash
    python -m venv virtualFolder
    ```
    Activate virtual environment
    ```bash
    virtualFolder/Scripts/Activate.ps1
    ```
    Install Python Modules with pip in the virtual environment

    ```bash
    pip install mysql-connector-python
    pip install pyfiglet
    pip install pandas
    ```

    Run application

    ```bash
    python application.py
    ```
3. Create a .gitignore file in your repository's root directory [virtualFolder] to tell Git which files and directories to ignore when you make a commit.

https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files?platform=windows

--------------------------------------------------------------------------------------.





Generating a new SSH key and adding it to the ssh-agent 
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent







## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

