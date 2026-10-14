# http-cache

An HTTP client wrapper with ETag support and an on-disk response cache.

## Why

Extracted from a larger codebase where it had grown organically.

## Install

```bash
pip install http-cache
```

## Usage

```python
from http_cache import httpCache

result = httpCache("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
