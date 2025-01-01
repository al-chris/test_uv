# Test UV Project

Testing the Python UV package manager.

## Setup

1. Create a new directory:
    ```sh
    mkdir test_uv
    ```

2. Navigate into the directory:
    ```sh
    cd test_uv
    ```

## Usage

1. Run a Python script:
    ```sh
    uv run hello.py
    ```

2. Add the `requests` package:
    ```sh
    uv add requests
    ```

3. Add the `cachetools` package:
    ```sh
    uv add cachetools
    ```

4. Compile the `pyproject.toml` file:
    ```sh
    uv pip compile pyproject.toml
    ```