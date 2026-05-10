# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

A sandbox repository for experimenting with Claude Code features, workflows, and AI-assisted development patterns.

## Commands

### Python
```bash
python training/test.py        # Run the test script
python -m pytest               # Run tests (if pytest is added)
python -m pytest -k "name"     # Run a single test by name
```

### Git
```bash
git status                     # Check uncommitted changes
git push origin main           # Push to remote
```

## Structure

- `training/` — hands-on exercises and experiment scripts
  - `Claude.md` — this guidance file
  - `test.py` — scratch/test Python scripts

## Notes

- This repo is for learning; scripts in `training/` are standalone experiments, not a connected application.
- Add new experiments as separate `.py` files under `training/`.
- Update this file as new tools, patterns, or conventions are established.
