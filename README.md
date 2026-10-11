# url-signer

Generate and verify time-limited signed URLs using HMAC-SHA256.

## Why

Extracted from a larger codebase where it had grown organically.

## Install

```bash
pip install url-signer
```

## Usage

```python
from url_signer import urlSigner

result = urlSigner("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
