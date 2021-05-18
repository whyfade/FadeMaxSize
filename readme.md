# Manual
```python
from FadeMaxSize.findMax import find_max_file

answer = find_max_file('path')
print(answer)
"""
{
    'file': 'path to largest file',
    'size': 1234 # Largest file size in kilobytes
}
"""
```


### How to start tests?
'python -m unittest -v tests/test_find.py' from /max_size