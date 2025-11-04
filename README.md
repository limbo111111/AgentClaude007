# AgentClaude007

A collection of specialized Claude AI agents for various development tasks.

## Overview

This repository contains custom Claude AI agents that can be used with GitHub Copilot and other Claude-based development tools. Each agent is specialized for specific tasks and comes with detailed prompts and instructions.

## Available Agents

The agents are located in the `.github/agents/` directory:

- **auth-route-debugger** - Debug authentication-related issues with API routes
- **auth-route-tester** - Test authenticated endpoints and routes
- **auto-error-resolver** - Automatically fix TypeScript compilation errors
- **code-architecture-reviewer** - Review code architecture and design patterns
- **code-refactor-master** - Master code refactoring and optimization
- **documentation-architect** - Create and maintain comprehensive documentation
- **frontend-error-fixer** - Fix frontend-related errors and issues
- **plan-reviewer** - Review and validate development plans
- **refactor-planner** - Plan code refactoring strategies
- **web-research-specialist** - Research web technologies and solutions

## Usage

These agents are designed to work with GitHub Copilot Workspace and other Claude AI integrations. Each agent file contains:

- **Name**: Unique identifier for the agent
- **Description**: What the agent does and when to use it
- **Instructions**: Detailed prompts and workflows for the agent
- **Tools**: Available tools the agent can use (if applicable)

## Structure

```
AgentClaude007/
├── .github/
│   └── agents/          # Agent definition files
│       ├── README.md    # Agent documentation
│       └── *.md         # Individual agent files
└── README.md            # This file
```

## Contributing

Feel free to contribute new agents or improve existing ones. Each agent should:

1. Have proper YAML frontmatter with name, description, and optional color/tools
2. Include clear instructions and workflows
3. Provide examples of when to use the agent
4. Follow the existing agent structure

## License

This repository is open source and available for use in your own projects.

## Source

These agents were originally sourced from the [mdk-predator](https://github.com/limbo111111/mdk-predator) repository and adapted for general use.
