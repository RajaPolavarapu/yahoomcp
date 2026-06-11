# Contributing

Thanks for your interest in contributing to this project.

## How to contribute

1. Fork the repository.
2. Create a new branch from `main`.
3. Make your changes with clear, focused commits.
4. Test your changes locally.
5. Open a pull request with a clear description of what changed and why.

## Development setup

```bash
git clone https://github.com/RajaPolavarapu/yahoomcp.git
cd yahoomcp
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Pull request guidelines

- Keep pull requests small and focused.
- Explain the problem and the solution.
- Include screenshots, logs, or examples when useful.
- Do not commit API keys, credentials, `.env` files, or private data.
- Update the README when behavior, setup, or usage changes.

## Code quality

Before opening a pull request, check that:

- The server starts successfully.
- Existing tools still work.
- New functionality has a clear use case.
- Error handling is reasonable.

## Security

Do not open public issues for security vulnerabilities. Follow the process in `SECURITY.md` instead.
