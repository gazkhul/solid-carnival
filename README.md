# solid-carnival
customer servers config

## install
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh

cd solid-carnival
uv venv .venv
source .venv/bin/activate
uv sync

# dev env
# uv pip install -r requirements.txt
# pre-commit install