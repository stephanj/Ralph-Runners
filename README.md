# Ralph Runners

**A cross-platform desktop app for running Claude Code CLI in autonomous agent loops**

Ralph Runners is a JavaFX desktop application that automates PRD (Product Requirements Document) task execution using Claude Code CLI. It runs tasks in iterative "Ralph Wiggum" loops until completion, with automatic status tracking and optional cloud sync.

## What is Ralph Runners?

- **Autonomous Task Execution** - Import PRD task files and let Claude Code work through them automatically
- **Cross-Platform** - Native installers for macOS, Windows, and Linux
- **Progress Tracking** - Real-time visibility into task completion with automatic status updates
- **Cloud Sync** - Optional Firebase integration for syncing task status across devices

## This Repository

This is the **public issue tracker** for Ralph Runners. Use it to:

- Report bugs
- Request features
- Ask questions
- Discuss improvements

The source code is maintained in a private repository.

## Reporting Issues

When reporting a bug, please include:

1. **Operating system** and version
2. **Ralph Runners version** (from the app's About menu)
3. **Steps to reproduce** the issue
4. **Expected behavior** vs actual behavior
5. **Error messages** or logs if available

## Links

- **Website**: [ralphrunners.com](https://ralphrunners.com)
- **Downloads**: [ralphrunners.com/download](https://ralphrunners.com/download)

## PRD File Format

Ralph Runners processes JSON task files in this format:

```json
[
  {
    "id": "TASK-001",
    "category": "backend",
    "title": "Task title",
    "description": "Detailed description",
    "steps": ["Step 1", "Step 2"],
    "passes": false
  }
]
```

## Requirements

- [Claude Code CLI](https://claude.ai/code) installed and authenticated

## License

Copyright 2026 Stephan Janssen BV. All rights reserved.
