## Installation

This project uses [UV](https://github.com/astral-sh/uv) for Python package management. UV is a fast Python package installer and resolver.

### Installing UV

#### macOS
```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
```

Or using Homebrew:
```bash
    brew install uv
```

### Using Jupyter from VS Code

1. **Create a project.
```bash
    uv init project
```

2. **Move into the project directory.
```bash
    cd project
```

3. **Add ipykernel as a dev dependency.
```bash
    uv add --dev ipykernel
```

4. **Open the project in VS Code.
```
    code .
```

### Using UV with this project

1. **Install Python with specific version:**
   ```bash
   uv python install 3.12.10
   ```

2. **Activate virtual environment:**
   ```bash
   source .venv/bin/activate
   ```

3. **Install dependencies:**
   ```bash
   uv sync
   ```

4. **Run the project:**
   ```bash
   uv run python main.py
   ```

5. **Add new dependencies:**
   ```bash
   uv add package-name
   ```
