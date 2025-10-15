# libadctf

A Python library for [describe your library's purpose here].

## Installation

### From PyPI (when published)

```bash
pip install libadctf
```

### Development installation with uv

```bash
# Clone the repository
git clone https://github.com/yourusername/libadctf.git
cd libadctf

# Install in development mode
uv pip install -e .
```

## Development

This project uses `uv` for dependency management and packaging.

### Setting up development environment

```bash
# Install development dependencies
uv pip install -e ".[dev]"
```

### Running tests

```bash
pytest
```

### Building the package

```bash
uv build
```

### Publishing to PyPI

```bash
# Build the package
uv build

# Publish to PyPI (requires API token)
uv publish
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
