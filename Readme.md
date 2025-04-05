## Setting up the Python Environment

To set up the virtual environment and install the required dependencies, follow these steps:

```bash
# 1. Create a virtual environment
python -m venv .venv

# 2. Activate the virtual environment (Windows)
.venv\Scripts\activate

# For macOS/Linux, use:
# source .venv/bin/activate

# 3. Install dependencies from requirements.txt
python -m pip install -r requirements.txt