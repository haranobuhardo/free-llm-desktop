# Free LLM Desktop

---

## Introduction

This project is a desktop client for accessing [Perplexity AI Labs](https://labs.perplexity.ai/) without the need to open a web browser. It is developed using Wails in Golang as an experiment to understand the Go language and to explore creating cross-platform desktop applications. 

### Why Perplexity AI Labs?
- It provides a streamlined interface to interact with various state-of-the-art Large Language Models (LLMs) such as Mistral 7B Instruct, Llama 2 13B, Llama 2 70B, Codellama 34B Instruct, and PPLX 70B Chat.
- **It is FREE!**

## Features

- **FREE**: Without the need of any subscription or even login (so far I think this is now the best one for daily simple task, e.g. fixing grammar)
- **Direct Access**: No need to open a web browser to access Perplexity Labs.
- **Multiple Models**: Interact with popular open-source LLMs.
- **Lightweight**: Optimized for low resource consumption.
- **Cross-Platform**: Compatible with multiple desktop operating systems. (currently built and tested only on Windows)

## Requirements

- Golang 1.18 or higher
- Wails v2.60 or higher

## Installation

- **Build from Source**
  ```bash
  git clone https://github.com/your_username/Perplexity-Desktop-Client.git
  cd Perplexity-Desktop-Client
  wails build
  ```

- **Use Released Version**
  Download the latest release and execute.

## Usage

Run the compiled binary to start. Use the UI to select an LLM and interact.

## Credits

All credit for the LLM models and their functionalities goes to [Perplexity Labs](https://labs.perplexity.ai/).

---

