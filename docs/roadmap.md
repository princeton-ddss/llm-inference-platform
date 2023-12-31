# Project Roadmap

A breakdown of the functionality we aim to provide in stages:

1. Command-line deployment of the LLM
2. Deployment of the LLM via web-based graphical user interface (GUI)
3. Providing easily accessible graphical user interfaces to interact with the
   LLM once it is running

## Status

|     | Deployment | Interaction |
| --- | ---------- | ----------- |
| CLI | testing    | development |
| GUI | tbd        | not started |

## Command-Line Deployment

**Status: Testing**

We provide a command-line tool for generating SLURM jobs that deploy a
pre-configured LM server on a compute node, with helpful utilities for
forwarding the port served by the LM and querying its API.

## GUI-based Deployment

**Status: tbd**

We provide a web-based graphical interface (like MyDella) with
textboxes/dropdown menus to choose an open-source LM and deploy it on Della.

The deployment interface can be made with
[Open OnDemand](https://openondemand.org/) or a simple web interface

## GUIs to interact with the LM

**Status: not started**

We provide several "supported" graphical interfaces for users that the LM server
will automatically be connected to after they request the job through the
MyDella-like interface.

Target GUIs:

- Chat
- Completion
- Batch zero/few-shot
