# Model Context Protocol (MCP).
> Learn MCP.

## Table of Contents
1. [About](#about)  
2. [References](#references)  
3. [Features](#features)  
4. [Getting Started](#getting‑started)
   - [Software and Versions](#software-and-versions)
   - [Prerequisites](#prerequisites)  
   - [Installation](#installation)
5. [Usage](#usage)  
6. [Roadmap](#roadmap)

---

## About
This repository serves as a dump of resources for learning MCP, including practice code and implementations.

## References
1. HuggingFace MCP Course: https://huggingface.co/learn/mcp-course/

## Features

## Getting Started

### Prerequisites and Assumptions
1. Python
2. Conda
3. All commands assume you start in the root directory of this git repository i.e. `.../learn-mcp/`.

### Software and Versions

### Installation
1. Clone this repository:
```git
git clone https://github.com/jayellho/learn-mcp.git
cd learn-mcp
```

2. Create and activate conda virtual environment `mcp` with python 3.11 and pip install `requirements.txt`.
```
conda create -n mcp python=3.11
conda activate mcp
pip install -r requirements.txt
```

3. Deactivate conda environment `mcp` when done.
```
conda deactivate
```

## Usage
1. Run MCP server `basic-server.py` for example:
```
cd code-snippets
mcp dev basic-server.py
```

## Roadmap
- [ ] placeholder
