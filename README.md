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

### [Bug Bounty Hunter](agents/bug-bounty-hunter-autogen.ipynb) 🐛
**Framework**: Microsoft AutoGen | **Model**: Anthropic Claude 3.5 Sonnet

Collaborative security testing system with specialized agents for scanning, analysis, reporting, and remediation. Features automated vulnerability discovery, comprehensive security reports, and multi-language code analysis.

### [Documentation Ghost Writer](agents/doc-ghostwriter-hf-agents.ipynb) 📝
**Framework**: HuggingFace Transformers Agents | **Model**: Llama 3.1 8B

Real-time documentation system that watches code changes and automatically generates comprehensive documentation. Features AST-based code analysis, template systems, and file system monitoring.

### [API Integration Speedrunner](agents/api-speedrunner-haystack.ipynb) ⚡
**Framework**: Haystack | **Model**: OpenAI GPT-3.5-turbo

Rapid API integration system that reads documentation and generates complete client libraries in multiple languages. Features OpenAPI parsing, code generation, and automated testing.

### [Viral Content Predictor](agents/viral-content-predictor-llamaindex.ipynb) 📈
**Framework**: LlamaIndex Agents | **Model**: OpenAI GPT-3.5-turbo

Advanced content analysis system that predicts viral potential and optimizes content for different social media platforms. Features real-time trend analysis and A/B testing support.

### [Academic Paper Implementation Bot](agents/academic-paper-bot-pydantic.ipynb) 🎓
**Framework**: PydanticAI | **Model**: OpenAI GPT-3.5-turbo

Automated research reproduction system that reads academic papers and implements algorithms with validation. Features arXiv integration, multi-language support, and reproducible project generation.

### [Full-Stack Feature Agent](agents/fullstack-feature-agent-cline-crewai.ipynb) 🚀
**Framework**: CrewAI | **Model**: Anthropic Claude 3.5 Sonnet

Complete development team simulation using 6 specialized agents for end-to-end feature implementation. Features automated code generation, testing, deployment, and project management with realistic team collaboration.

### [AI Code Reviewer with o1 Reasoning](agents/ai-code-reviewer-o1.ipynb) 🧠
**Framework**: OpenAI o1 | **Model**: OpenAI o1-preview

Advanced code review system using OpenAI's o1 reasoning model. Provides deep architectural analysis, security audits, performance optimization, and comprehensive code quality assessment.

### [Legacy Code Modernizer](agents/legacy-code-modernizer-autogen.ipynb) ⚡
**Framework**: AutoGen | **Model**: Anthropic Claude 3.5 Sonnet

Automated legacy code transformation system with 5 specialized agents for analysis, refactoring, testing, documentation, and validation. Modernizes codebases with pattern detection and automated upgrades.

### [Multi-Platform Content Repurposer](agents/multi-platform-content-repurposer-n8n.ipynb) 📱
**Framework**: n8n | **Model**: OpenAI GPT-4

Intelligent content automation using n8n workflows. Adapts content for 6 social platforms with AI-powered optimization, scheduling, and cross-platform publishing.

### [AI Influencer Network](agents/ai-influencer-network-elizaos.ipynb) 🌟
**Framework**: ElizaOS | **Model**: Multiple Claude 3.5 Sonnet instances

Multi-personality AI influencer management system. Creates and manages diverse AI personalities for social media with autonomous content generation and engagement.

### [Sales Pipeline Orchestrator](agents/sales-pipeline-orchestrator-langgraph.ipynb) 💼
**Framework**: LangGraph | **Model**: OpenAI GPT-4

Advanced sales automation using state machines. Features 8-stage pipeline with lead scoring, nurturing, deal management, and conditional routing for enterprise sales.

### [Customer Success Prediction Agent](agents/customer-success-prediction-agent.ipynb) 📊
**Framework**: scikit-learn + ML | **Model**: Multiple ML algorithms

ML-powered customer analytics system. Predicts churn, calculates health scores, and generates actionable insights using advanced machine learning and behavioral analysis.

### [AI Financial Analyst Team](agents/ai-financial-analyst-team-crewai.ipynb) 💰
**Framework**: CrewAI | **Model**: OpenAI GPT-4

6 specialized financial agents for comprehensive market analysis. Features equity research, risk management, portfolio optimization, and compliance monitoring with real financial data.

### [AI VTuber Studio](agents/ai-vtuber-studio-relevanceai.ipynb) 🎭
**Framework**: Relevance AI | **Model**: OpenAI GPT-4

Virtual content creator management system. Manages multiple AI VTuber personalities with content generation, livestream management, and performance analytics.

### [Personalized Learning Path Generator](agents/personalized-learning-path-generator.ipynb) 🎓
**Framework**: spaCy NLP | **Model**: spaCy + OpenAI GPT-4

AI-powered education system with learning style assessment, adaptive path generation, knowledge gap analysis, and progress tracking for personalized learning experiences.

### [AI Meme Generator with Market Integration](agents/ai-meme-generator-market-integration.ipynb) 😂
**Framework**: Hugging Face Transformers | **Model**: Multiple vision and text models

Viral meme generation system with market sentiment analysis, virality prediction, multi-platform optimization, and brand safety controls for social media success.

### [Competitive Intelligence Agent](agents/competitive-intelligence-agent.ipynb) 🔍
**Framework**: LangChain | **Model**: OpenAI GPT-4

Market analysis system with multi-source intelligence gathering, SWOT analysis, competitive positioning, and pricing intelligence for strategic business insights.

### [AI Legal Document Analyzer](agents/ai-legal-document-analyzer.ipynb) ⚖️
**Framework**: Unstructured | **Model**: OpenAI GPT-4

Legal document processing system with contract clause extraction, risk assessment, compliance checking, and automated legal analysis for complex documents.

### [Personal Health Optimization Agent](agents/personal-health-optimization-agent.ipynb) 🏥
**Framework**: Health Analytics (pandas, scikit-learn) | **Model**: ML algorithms

Comprehensive health analysis system with anomaly detection, pattern analysis, personalized recommendations, and risk assessment for optimal health management.

### [Open Source Contribution Maximizer](agents/open-source-contribution-maximizer.ipynb) 🤝
**Framework**: Celery + GitHub API | **Model**: OpenAI GPT-4

Intelligent open source contribution system using distributed task processing. Matches developers with opportunities, tracks contributions, and optimizes impact across the ecosystem.
