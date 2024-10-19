# Income GPT Mercor Hackathon Project

Welcome to the Mercor Hackathon project! Follow the instructions below to set up your development environment and get started.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following:

- Python version **>= 3.8.1** installed on your machine. Make sure to add Python to your system PATH during installation.
- A valid **OpenAI API key** set in `main.py`.

### Installation Steps

1. **Fork the Repository**
   - Click on the “Fork” button in the top right corner of the repository page.

2. **Clone the Repository**
   - Use the following command to clone the repository to your local machine:
     ```bash
     git clone <your_forked_repo_url>
     ```

3. **Open the Repository in Visual Studio Code**
   - Launch VS Code and open the folder containing the cloned repository.

4. **Upgrade Python Version**
   - If you haven’t already, download Python version **>= 3.8.1** from [python.org](https://www.python.org/downloads/) and ensure it’s added to your PATH during installation.

5. **Install Poetry**
   - Poetry is a Python package manager that simplifies dependency management. To install it, run the following command in your terminal:
     ```bash
     pip install poetry
     ```

6. **Set Default Terminal Profile**
   - Press `Ctrl + Shift + P` to open the command palette.
   - Search for and select **Terminal: Select Default Profile** and choose **Command Prompt**.

7. **Configure Poetry for VS Code**
   - Inside the VS Code terminal, navigate to your project folder and run:
     ```bash
     poetry config virtualenvs.in-project true
     ```
   - This command sets up the virtual environment within your project folder, allowing for better management of dependencies.

8. **Activate the Poetry Environment**
   - To activate the Poetry virtual environment, run:
     ```bash
     poetry shell
     ```

9. **Select the Poetry Interpreter**
   - Press `Ctrl + Shift + P`, then search for **Python: Select Interpreter**.
   - Ensure you select the interpreter associated with Poetry.

10. **Install Dependencies**
    - Run the following command to install the project dependencies:
      ```bash
      poetry install .
      ```

11. **Run the Application**
    - Finally, run the application using:
      ```bash
      poetry run python textbase/textbase_cli.py test main.py .
      ```

## Important Notes

- Remember to set your **OpenAI API key** in `main.py` to enable functionality.
- If you encounter any issues, please refer to the official Poetry documentation for troubleshooting.

Happy coding!
