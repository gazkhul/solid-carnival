# solid-carnival
customer servers config

## install
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh

cd solid-carnival
uv venv
source .venv/bin/activate
uv sync --no-default-groups

# dev env
uv sync
pre-commit install