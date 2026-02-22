# simple-password-gen

> Simple generate secure passwords with rules

[![PyPI version](https://badge.fury.io/py/simple-password-gen.svg)](https://pypi.org/project/simple-password-gen/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org)

## Installation

```bash
pip install simple-password-gen
```

## Quick Start

```python
from simple_password_gen import gen

# Basic usage
result = gen("your input here")
print(result)
```

## Features

- Simple, clean API with type hints
- Zero dependencies (pure Python)
- Python 3.8+ compatible
- Fully tested
- Lightweight (< 5KB)

## API Reference

### `gen(input)`

Main utility function.

**Parameters:**
- `input` — The input data to process

**Returns:** Processed result

### `batch(inputs)`

Process multiple inputs at once.

**Parameters:**
- `inputs` — List of inputs

**Returns:** List of results

## Examples

```python
from simple_password_gen import gen

# Example 1: Basic usage
result = gen("Hello World")

# Example 2: Batch processing
from simple_password_gen import batch
results = batch(["item1", "item2", "item3"])
```

## Running Tests

```bash
pip install pytest
pytest tests/
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT License - see [LICENSE](LICENSE) file for details.

---

### Learn More

**Want to build tools like this?** Check out the
**[Cybersecurity For Beginners](https://gumroad.com/l/cybersecurity-for-beginners)** course — it teaches you
step-by-step how to create useful Python utilities from scratch,
with real-world projects and best practices.

*Built with skills from [Cybersecurity For Beginners](https://gumroad.com/l/cybersecurity-for-beginners)*
