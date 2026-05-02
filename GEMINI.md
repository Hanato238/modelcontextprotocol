# Perplexity Search Extension for Gemini CLI

This extension allows Gemini CLI to use Perplexity's real-time web search and reasoning capabilities through the Model Context Protocol (MCP).

## Prerequisites

- A Perplexity API Key. You can get one from the [Perplexity API Settings](https://www.perplexity.ai/settings/api).

## Installation

To install this extension, run the following command in your terminal:

```bash
gemini extensions install ./workspace/mcp-servers/perplexity-ask
```

## Configuration

You must set the `PERPLEXITY_API_KEY` environment variable for the extension to work.

### On Windows (PowerShell):
```powershell
$env:PERPLEXITY_API_KEY = "your-api-key-here"
```

### On macOS/Linux:
```bash
export PERPLEXITY_API_KEY="your-api-key-here"
```

Alternatively, you can add it to your `~/.bashrc`, `~/.zshrc`, or system environment variables.

## Usage

Once installed, Gemini will automatically have access to the Perplexity tools. You can ask questions that require real-time information, such as:
- "What are the latest news about X?"
- "Search for the latest research on Y."
