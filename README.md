<div align="center">

![Logo of DOCAGENT](./docs/docagent-logo.png)

# **DOCAGENT**

A Dev-first open-source Autonomous AI agent framework to execute Document Processing Tasks. It enables developers to build, manage & run useful autonomous Document AI agents quickly and reliably.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

</div>

## Table of contents

- [Why DOCAGENT?](#why-docagent)
- [Getting Started](#getting-started)
- [Key Features](#key-features)
- [Contribution](#contribution)
- [License](#license)
<!-- - [Examples](#examples)
  - [Quick Tutorial](#quick-tutorial)
  - [Write Job Descriptions](#write-job-descriptions)
  - [Trip Planner](#trip-planner)
  - [Stock Analysis](#stock-analysis) -->
<!-- - [How CrewAI Compares](#how-crewai-compares) -->

<!-- - [Telemetry](#telemetry) -->

## Why DOCAGENT?

Intelligent Document Processing (IDP) involves lot of process & pipelines to produce the defined results.
DOCAGENT is designed to enable AI agents to assume roles, execute tasks, and operate in a cohesive unit - much like a systematic team. Whether you're building an invoice processor, claim summarizer, or a multi-agent finanicial statement analyzer, DOCAGENT provides the backbone & ecosystem for developing sophisticated multi-agent document processor system.

## Getting Started
Requires Python 3.10+

```shell
pip install git+ssh://git@github.com/renixinformatics/docagent.git
```

or

```shell
pip install git+https://github.com/renixinformatics/docagent.git
```

## Contribution

DOCAGENT is open-source and we welcome contributions. If you're looking to contribute, please:

- Fork the repository.
- Create a new branch for your feature.
- Add your feature or improvement.
- Send a pull request.
- We appreciate your input!

### Installing Dependencies

```bash
uv lock
uv sync
```

### Virtual Env

```bash
uv venv
```

### Pre-commit hooks

```bash
pre-commit install
```

### Running Tests

```bash
uvx pytest
```

### Running static type checks

```bash
uvx mypy
```

### Packaging

```bash
uv build
```

### Installing Locally

```bash
pip install dist/*.tar.gz
```

## License

DOCAGENT is released under the [MIT License](https://github.com/renixinformatics/docagent/blob/main/LICENSE).
