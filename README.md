# 👋 Hello

This project is for testing [uv](https://docs.astral.sh/uv/) as a Python package and project manager.

## Local installation

1. Clone repository:

```bash
git clone https://github.com/janmirco/hello.git
```

2. Go to your `uv` project and install `hello` in editable mode:

```bash
uv add --editable <PATH_TO_HELLO_REPO>
```

## Usage

After installation, you can use `hello` in your Python scripts:

```python
import hello as h
h.say.hi()
h.say.bye()
```
