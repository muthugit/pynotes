# Read JSON file

### Side 2

```python
import json
class JSONReader:
    def __init__(self, file_path: str):
        self.file_path = file_path
    def read(self):
        with open(self.book_path, 'r') as myfile:
            data = myfile.read()
        return json.loads(data)
if __name__ == "__main__":
    reader = JSONReader("/tmp/a.json")
    print(reader.read())
```

### Side 3
