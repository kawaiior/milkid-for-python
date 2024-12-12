# Milkid for python

[Milkid](https://github.com/akirarika/milkid) is a highly customizable distributed unique ID generator written in TypeScript.

# Installation
```bash
pip install milkid
```

# Usage
```python
from milkid import IdGenerator

id_generator = IdGenerator(length=24, timestamp=True, hyphen=True, fingerprint=True, hash_seed=1234567)

print(id_generator.create_id("test"))  # Rbge8Id-RbXmewrZ1Ie7-7B22X
```