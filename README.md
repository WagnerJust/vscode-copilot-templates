# VSCode Copilot Extention Template

This repository contains templates for creating custom code assist agents for your VSCode Copilot Extention.

## Setup

1. Create a `.github` directory in the root directory in your codebase. Copy the contents of `dot-github` into the directory.

2. The `setup-instructions.md` file contains a list of questions to help you build your `copilot-instructions.md` file for your repository. You can run through these questions with an AI chat of your choice.

## Chatmodes

The chatmodes are designed to be modular and customizable.

### Planner Chatmode

The only chatmode that is not universal is the `Planner.chatmode.md`. You will need to update it with your custom prompt file personas.

### Custom Tools

The tools in the chatmodes are customizable. If you choose to use custom tools from mcp servers, like `context7`, you must create a `.vscode/mcp.json` file with the server configurations defined.

## Prompts

The prompt files are customizable to whatever personas or developer team roles you need. You can create new prompt files or modify the existing ones to suit your needs.
