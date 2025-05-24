![CI](https://github.com/Bruh-Ryan/sample_project2/actions/workflows/ci.yml/badge.svg)

- name: Check code formatting with Black
  run: |
    pip install black
    black --check .

