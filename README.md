# AItools
A place where I store my favorite AI tools and their configuration. In general I prefer tools that I can run locally. My main points of interest are chatbots for document management, text processing in OnlyOffice, basic Python coding in VS Code and image manipulation. Those are running on my daily laptop (Win 11, Intel i7 with integrated XE Graphics, 16 GB RAM) and/or my dev machine (Linux Mint, DELL Precision 7530, 16 GB RAM) 

# Current Setup
## LM Studio
https://lmstudio.ai

License : MIT 

A tool to run LLMs locally, can run multiple at the same time. I prefer it over Ollama because it has a lot of controls in the GUI to fine-tune the way you load the model. It also has an integrated chatbot with realtime logging which is very useful when debugging or optimising.

## Anything LLM
https://anythingllm.com
License : MIT
An advance chatbot interface that manages LLM providers, can run its own thru a local Ollama install. Allows to connect to different providers, build RAG with document management, build and use agents using different models in the same workflow. Comes with a great community hub with lots of great workflows and agent configurations.
Runs locally in a container, they also provide a setup for Mac and Windows.

## Continue
https://docs.continue.dev/
License : Apache 2.0
An extension for VS Code where you can connect any LLM; including the one you run locally with LM Studio or Ollama.
Continue is a full CI/CD environment, I only use the VS module.

## n8n
https://n8n.io
License : OpenCore https://github.com/n8n-io/n8n/blob/master/LICENSE.md
A web workflow editor for AI workflows.
Runs locally in a container.

## ComfyUI
https://www.comfy.org/
License : GPL 3.0
A web node-based interface to connect image processing and generation models, 2D and 3D. Comes with super useful workflow presets. 
Runs locally in a container, they also provide a setup for Mac and Windows. Doesn't run 

# Models
Models that I run locally inside LM Studio

## google/gemma-3-1b
Super light, does a pretty good job on basic tasks like simple Python coding and text manipulation. 
Cannot use tools

## liquid/lfm2-1.2b
Slightly heavier than gemma-3-1b but fast execution and can use tools


# Tools to evaluate
## LocalAI 
https://localai.io/
A suite of tools ( that can run in Containers) for running LLMs locally (LocalAI), configure Agents (LocalAGI) and manage "knowledge" bases (LocalRecall)
The GUI is a little too funky to my taste but it has some interesting features.
Runs locally in a container.

## Memori
https://github.com/MemoriLabs/Memori
A tool to manage knowledge and context and store it in a database 

## EXO
https://github.com/exo-explore/exo
License : Apache 2.0
A tool to build AI clusters 



