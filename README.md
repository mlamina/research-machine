# Research Machine

This project uses the [Pilot CLI](https://github.com/PR-Pilot-AI/pr-pilot-cli) to automate research tasks and draw conclusions from the data.

## How it works

Every "research project" is in its own directory:

- [Donald Trump 2024 Election Hypothesis](donald-trump-2024-election/README.md)
- [Microplastics Cause Cancer](microplastics-cause-cancer/README.md)

Each research project is defined by:
1. A hypothesis 
2. A backlog of research items
3. A knowledge base of research findings

### Creating a new research project

To create a new research project for a hypothesis, use the `pilot create-project` command:

```shell
➜  research-machine git:(main) pilot run create-project              
> Hypothesis: Large Language Models can be considered a form of consciousness
╭──────────────────────────────────────────────────── Result ────────────────────────────────────────────────────╮
│ The new research project has been initiated with the following details:                                        │
│                                                                                                                │
│  • Project Slug: large-language-models-consciousness                                                           │
│  • File Created: large-language-models-consciousness/README.md                                                 │
│                                                                                                                │
│ The README file contains the hypothesis, a backlog of research questions, a validation approach, and an empty  │
│ table of contents section.                                                                                     │
╰────────────────────────────────────────────────────────────────────────────────────────────────────────────────╯
```

This will initialize the project directory with a `README.md` file that contains the hypothesis, a backlog of research questions, a validation approach, and an empty table of contents section.

### Iterating on a research project



## How to Use This Project

The user can use `pilot` commands to interact with the project:

```shell
Usage: pilot run [OPTIONS] COMMAND [ARGS]...

  🚀 Run a saved command.

  Create new commands by using the --save-command flag when running a task.

Options:
  --help  Show this message and exit.

Commands:
  analyze         Analyze a knowledge base and draw conclusions about the...
  create-project  Create a new research project
  iterate         Do research on a projects backlog item
```
