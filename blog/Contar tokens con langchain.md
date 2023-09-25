```python
from transformers import AutoTokenizer
from embedding_manager import models

tokenizer = AutoTokenizer.from_pretrained(
f"""sentence-transformers/{paraphrase-multilingual-MiniLM-L12-v2}"""
)

tokens = tokenizer.encode("Texto de prueba")

print("tokens:", len(tokens))
```
