# vecnotes

Semantic search over local notes with embeddings

## Getting started

```bash
pip install -r requirements.txt
```

## How to use

```bash
python search.py ./notes
>> how do I back up my database?
```

## Features

- Reranks by recency when scores tie
- Vectors cached to .npy so re-runs are instant
- sentence-transformers when available, TF-IDF fallback
- Interactive REPL and one-shot modes

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .gitattributes
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── requirements.txt
└── search.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
