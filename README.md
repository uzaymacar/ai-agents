# AI Agents

**NOTE**: *This repository is still in progress and will be updated in the near future. While I started putting these agents together nearly a year ago, the AI agents landscape has evolved significantly since then and things might be out-of-date.*

This is a repository collecting various AI agents I've worked on.

Some of them I use frequently and others I programmed for fun or learning.

They cover a wide range of **frameworks** (e.g. LangGraph, LangChain, CrewAI, Ollama), **models** (e.g. Anthropic, DeepSeek R1), **tools** (e.g. YouTube API, LinkedIn API), and **topics** (e.g. video summarization, podcast outline, reasoning).

I hope you find them useful, feel free to use them in your projects. You can find all of the agents in the `agents/` directory.

## Agents

### [YouTube Video Summary](agents/youtube-video-summary.ipynb)

Summarizes a given YouTube video. Uses LangGraph, LangChain, LangSmith, Anthropic, and YouTube API.

### [Podcast Outline Writer](agents/podcast-outline.ipynb)

Generates a podcast outline based on a given guest and a given podcast topic. Uses CrewAI and Anthropic.

### [DeepSeek R1 Agent](agents/deepseek-reasoning-agent.ipynb)

A reasoning agent using the DeepSeek R1 model. Uses Langchain and Ollama.

### [Email Enhancer Agent](agents/email-enhancer-agent.ipynb)

A 4-step email enhancement agent that researches best practices, improves subject lines, enhances content, and composes professional emails. Uses smolagents and OpenAI's gpt-4o-mini model.