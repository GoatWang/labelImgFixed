uv venv --python cpython-3.8.20-linux-x86_64-gnu
source .venv/bin/activate
uv sync 
uv build
uv pip install -e .
