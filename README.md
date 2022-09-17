# GUIDE use tsrc

## Requirements
- Python version 3

## Setup

Create the workspace
```
mkdir pbl6
cd pbl6
```

Install `tsrc` tool - help manage many repos
```
pip install tsrc
tsrc init git@github.com:hovanvydut/pbl6.git
```

Synchronize all the repositories in the workspace (git pull):
```
tsrc sync
```