### Development Setup

```bash
# Clone the repository
git clone https://github.com/Pantheon-Security/medusa.git
cd medusa

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows

# Install in development mode
pip install -e ".[dev]"

# Verify installation
medusa --version
```

### Running Tests

```bash
pytest tests/ -v
```