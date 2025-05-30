# Workshop Solutions

This directory contains the Python solutions for the workshop assignments. Each solution is in its own Python file.

## File Structure

```
solutions/
├── README.md
├── pyproject.toml
├── poetry.lock
├── assignment-1.py    # Solution for "Your First Agent"
├── assignment-2.py    # Solution for "Content Creation with Guardrails"
├── assignment-3.py    # Solution for "Fraud Detection Workflow"
└── assignment-4.py    # Solution for "AI-Powered Onboarding System"
```

## Requirements

All solutions share the same requirements:
- Python >=3.10 <3.13
- CrewAI
- OpenAI API key
- SerperDev API key

## Setup

1. Install Poetry if you haven't already:
   ```bash
   curl -sSL https://install.python-poetry.org | python3 -
   ```

2. Install dependencies:
   ```bash
   poetry install
   ```

3. Set up your API keys:
   ```bash
   # On macOS/Linux
   export OPENAI_API_KEY='your-key'
   export SERPER_API_KEY='your-key'
   
   # On Windows
   set OPENAI_API_KEY=your-key
   set SERPER_API_KEY=your-key
   ```

## Running the Solutions

To run a specific solution:
```bash
poetry run python assignment-1.py  # For the first assignment
poetry run python assignment-2.py  # For the second assignment
# and so on...
```

## Note

These solutions are provided as reference implementations. It's recommended to try solving the assignments on your own before looking at the solutions. 