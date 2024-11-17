# Install `uv`

- Powershell with administrative right
  - `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
  - Close and reopen powershell (normal right)

# Check python

- `uv python list`

# Install python

- `uv python install 3.12`

# Virtual environment

- `uv venv`
  - Or to be more specific `uv venv --python 3.12`

# Install packages

- `uv pip install jupyterlab ipykernel pandas scikit-learn matplotlib seaborn openpyxl ruff`

# Install VSCode extensions

- Python Extension Pack (v1.7.0)
- Jupyter (v2023.11.1100101639)
  - This is not the latest release.

# Select python interpreter

- `Ctrl` + `Shift` + `p`
  - `Python: Select Interpreter`
  - Find `python.exe` under `C:\Users\[USER]\.venv\Scripts`

# Run python file

- Create `hello.py1` and type some code.
- Run file from the play button.

# Run Jupyter Notebook

- Create `hello.ipynb`
- Click `Select Kernel` at the top right.
- Click `+ Code` and type some code.
- Click play button.
