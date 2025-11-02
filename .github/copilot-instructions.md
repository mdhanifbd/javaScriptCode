# AI Coding Agent Instructions

## Project Overview
This is a JavaScript codebase running in a Node.js environment. The project is set up with dev containers for consistent development environments across machines.

## Development Environment
- Node.js 22.x (Debian Bookworm-based container)
- Development happens inside a dev container defined in `.devcontainer/devcontainer.json`
- Dependencies are managed via Dependabot with weekly updates configured in `.github/dependabot.yml`

## Project Structure
```
.
├── .devcontainer/       # Dev container configuration
│   └── basic01/        # Basic JavaScript examples
├── .github/            # GitHub configurations
└── README.md
```

## Key Files and Components
- `.devcontainer/devcontainer.json`: Defines the development container configuration using Node.js 22 on Debian
- `.github/dependabot.yml`: Manages automatic dependency updates for dev containers
- `.devcontainer/basic01/test.js`: Example JavaScript file showing basic code structure

## Development Workflow
1. All development should be done within the dev container environment
2. JavaScript files should be placed in appropriate subdirectories under `.devcontainer/`
3. Follow standard Node.js coding conventions

## Dependencies and Updates
- The project uses Dependabot to automatically check for updates to the dev container configuration
- Updates are scheduled weekly as defined in `.github/dependabot.yml`

## Notes for AI Agents
- When creating new JavaScript files, follow the basic structure shown in `basic01/test.js`
- Respect the dev container environment when suggesting dependencies or runtime commands
- Consider the Node.js 22.x environment when providing code suggestions

---
Note: This is a starter template based on the current codebase structure. Updates may be needed as the project evolves.