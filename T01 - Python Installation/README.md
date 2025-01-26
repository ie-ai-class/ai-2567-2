# Install `uv`

- Powershell with administrative right
  - `powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"`
  - Close and reopen powershell (normal right)

# Win 32

- `New-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Control\FileSystem" -Name "LongPathsEnabled" -Value 1 -PropertyType DWORD -Force`

# Check python

- `uv python list`

# Install python

- `uv python install 3.12`

# Virtual environment

- `uv venv myenv`
  - Or to be more specific `uv venv --python 3.12`

# Activate scripts

- `.\myenv\Scripts\Activate`

# Install packages

- Sklearn
  - `uv pip install jupyterlab ipykernel pandas scikit-learn matplotlib seaborn openpyxl ruff`
- Time Series
  - `uv pip install sktime statsmodels pmdarima tbats numpy==1.26.3`
  - Need `numpy==1.26.3` due to [error](https://stackoverflow.com/questions/78634235/numpy-dtype-size-changed-may-indicate-binary-incompatibility-expected-96-from).

# Install VSCode extensions

- Python Extension Pack (v1.7.0)
- Jupyter (v2023.11.1100101639)
  - This is not the latest release.
- Ruff (v2024.54.0)

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

# Misc

- Set format on save
- Set pythong formatter (by running formatting once)
