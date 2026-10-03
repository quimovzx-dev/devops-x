# DEVOPS-X 🐚

[![CI](https://github.com/quimovzx-dev/devops-x/actions/workflows/ci.yml/badge.svg)](https://github.com/quimovzx-dev/devops-x/actions/workflows/ci.yml) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

A portable Bash developer/system automation toolkit for quick diagnostics and repeatable maintenance tasks.

## Features
- System, network, disk and process diagnostics
- Git repository status snapshot
- Project scaffolding with `init`
- Safe log-tail helper
- Optional cache/build cleanup
- Shell syntax checks in CI

## Usage
```bash
chmod +x devops-x
./devops-x system
./devops-x network
./devops-x disk
./devops-x processes
./devops-x init my-project
./devops-x git-status
./devops-x logs /path/to/log
./devops-x cleanup
```

## Quality
Run locally with `bash -n devops-x`. CI also runs ShellCheck.

## License
MIT
