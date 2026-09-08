# meeting-scribe

Whisper wrapper that outputs timestamped markdown

## How to use

```bash
python transcribe.py meeting.mp3
# -> meeting.notes.md
```

## Installation

```bash
pip install -r requirements.txt
# needs ffmpeg installed
```

## What it does

- Outputs markdown with timestamps you can skim
- Batch mode for a folder of recordings
- Segments grouped into 5-minute sections
- Local whisper, no API key needed

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── requirements.txt
└── transcribe.py
```

## FAQ

**Is this production ready?**  
It works for my use case; review the code before relying on it.

**Why no framework?**  
The stdlib covers what this project needs.

## License

MIT. Do whatever you want.
