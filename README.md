## Setup & Run Instructions

### 1. Install Python

First, update your package manager and install Python < 3.11 and the `venv` module for creating virtual environments.

```bash
sudo apt-get update
sudo apt-get install -y python3.10 python3.10-venv
```

### 2. Create and Activate a Virtual Environment

Next, create a virtual environment to isolate the project's dependencies.

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

With the virtual environment activated, install the required packages using `pip` and the `pyproject.toml` file.

```bash
pip install -e .
```

### 4. Run the Application

You can now run the application with the following command:

```bash
python main.py
```

### 5. Access the Application

The application will be running at `http://127.0.0.1:10030`. You can access it by opening this URL in your web browser.
