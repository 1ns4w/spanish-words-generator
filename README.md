# Getting started

To get started, follow the next instructions:

```bash
cd spanish-words-generator
```

```bash
python3 -m venv .venv
```

```bash
source ./.venv/bin/activate
```

```bash
pip3 install -r requirements.txt
```

```bash
python3 ./src/app.py
```

# Examples

Create or write 365 words of length 5 to a file called "palabras5.txt" in the current folder.
```python
outfile_path = "./palabras5.txt"
getSpanishWords(5, 365, outfile_path)
```

Return an array of 365 words of length 5 and assign it to words.
```python
words = getSpanishWords(5, 365)
print(words) # [...]
```
