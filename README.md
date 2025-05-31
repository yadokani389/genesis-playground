```
nix develop
uv sync
uv run src/drone/hover_train.py
PYOPENGL_PLATFORM=glx uv run src/drone/hover_eval.py
```
