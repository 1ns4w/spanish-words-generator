# Dependencies

To get started, make sure to create a virtual enviroment and install the project dependencies.
```bash
cd spanish-words-generator
```

```bash
python -m venv .venv
```

```bash
pip install -r requirements.txt
```

# Examples
This example will write words of length `n` to a file called "wordle.txt". If the file doesn't exist, it will create it and write to it.
```python
getSpanishWords(5, "wordle.txt")
```

This example will return an array of words of length `n`.
```python
getSpanishWords(5)
```
