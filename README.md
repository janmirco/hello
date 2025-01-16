# 👋 Hello

This project is for testing [uv](https://docs.astral.sh/uv/) as a Python package and project manager.

## Local installation

1. Clone the repository: `git clone https://github.com/janmirco/hello.git`
2. Go to your project and initialize it: `uv init`
3. Install the project in editable mode: `uv add --editable <PATH_TO_HELLO_REPO>`

## Usage

After installation, you can use the `hello` package in your Python scripts:

```python
import hello as h
h.say.hi()
h.say.bye()
```
