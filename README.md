# Template

## Installation

0.  **Clone the repository:**

    Before you begin, you need to clone the project's source code repository.
 
    ```bash
    git clone https://github.com/UmbrellaLeaf5/template_python_usual.git
    ```

    Go to the directory where the repository was cloned:

    ```bash
    cd template_python_usual
    ``` 


1.  **Creating a virtual environment:**

    Open a terminal or command prompt in the root directory of your project (where the `requirements.txt` file is located) and run the following command to create a virtual environment named `.venv`:

    ```bash
    python3 -m venv .venv
    ```

    or

    ```bash
    python -m venv .venv
    ```

    *   If you only have `Python 3` installed, you can use `python` instead of `python3`.
    *   If the virtual environment already exists (you created it earlier), skip this step.


2.  **Activating the virtual environment:**

    Activate the virtual environment so that `Python` uses the libraries installed inside it:

    *   **Linux/macOS:**

        ```bash
        source .venv/bin/activate
        ```

    *   **Windows (Command Prompt):**

        ```cmd
        .venv\Scripts\activate
        ```

    *   **Windows (PowerShell):**

        ```powershell
        .venv\Scripts\Activate.ps1
        ```

    Once activated, you will see `(.venv)` at the beginning of the terminal line, indicating that the virtual environment is active.


3.  **Installing dependencies from `requirements.txt`:**

    Install all libraries listed in the `requirements.txt` file by running the following command:

    ```bash
    ./.venv/Scripts/pip install -r requirements.txt
    ```

    or simply:

    ```bash
    pip install -r requirements.txt
    ```
