# 🤖 AI-Project

My home base for learning and building with **AI**: LLMs, prompts, AI agents, AI tools, and AI apps.
I'm a beginner, so this repo is about **steady progress**, not perfection.

---

## 🧭 What goes here (and what doesn't)

| ✅ Belongs in AI-Project | ❌ Goes in my [Machine-Learning](https://github.com/mskykevin/Machine-Learning) repo |
| --- | --- |
| Using LLMs (Claude, ChatGPT, local models) | Classic ML (regression, classification, clustering) |
| Prompt engineering and context engineering | Training or fine-tuning models |
| AI agents, tools, and MCP servers | Neural networks and deep learning theory |
| RAG apps (chat with your documents) | Data science, pandas, scikit-learn |
| AI coding assistants and AI automation | Math and statistics for ML |

**Rule of thumb:** if I'm *using or building on top of* AI models → here.
If I'm *training or studying how models learn* → Machine-Learning.

## 🎯 Goals

- Understand how LLMs, prompts, and AI agents work
- Build small, real AI projects (chatbots, agents, automations)
- Get comfortable with Python, Git, and GitHub along the way
- Make my **first open-source contribution** to an AI project

## 🗂️ How this repo is organized

| Folder | What goes in it |
| --- | --- |
| `projects/` | AI projects I build (one folder per project) |
| `prompts/` | Prompts I've written or collected that work well |
| `notes/` | What I learned from AI courses, videos, and articles |
| `practice/` | Small exercises (calling an AI API, building a tool, etc.) |
| `contributions/` | Notes on open-source PRs/issues I worked on |

> Folders get created as I add things to them.

## 📅 Learning log

| Date | Topic | What I did | Link |
| --- | --- | --- | --- |
| 2026-10-11 | Getting started | Created this repo and picked AI repos to follow | — |

---

## ⭐ AI repos I'm following (beginner-friendly + trending)

Star counts as of Oct 2026. **Start at the top and work down.**

### Step 0: Practice making a contribution

| Repo | Why |
| --- | --- |
| [firstcontributions/first-contributions](https://github.com/firstcontributions/first-contributions) | Step-by-step guide to your very first pull request. Do this first! |

### 📚 Courses: learn the concepts

| # | Repo | ⭐ | Why it's great for beginners |
| --- | --- | --- | --- |
| 1 | [microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) | 121k | 21 lessons on building with generative AI. Best starting point. |
| 2 | [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | 77k | 18 lessons on AI agents, the hottest topic right now |
| 3 | [huggingface/agents-course](https://github.com/huggingface/agents-course) | 33k | Free Hugging Face course on agents, with a certificate |
| 4 | [microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) | 17k | Learn MCP, the standard way to connect AI to apps and tools |
| 5 | [dair-ai/Prompt-Engineering-Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) | 79k | Prompting, RAG, and agents explained clearly |
| 6 | [f/prompts.chat](https://github.com/f/prompts.chat) | 173k | Huge community prompt collection (formerly "Awesome ChatGPT Prompts"). Adding a prompt is an easy first PR. |

### 🍳 Cookbooks: copy-paste examples

| # | Repo | ⭐ | Why |
| --- | --- | --- | --- |
| 7 | [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | 53k | Ready-to-run examples using Claude |
| 8 | [openai/openai-cookbook](https://github.com/openai/openai-cookbook) | 77k | Ready-to-run examples using the OpenAI API |
| 9 | [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) | 141k | 100+ small AI apps and agents to copy and learn from |

### 🧰 AI tools: use AI day to day

| # | Repo | ⭐ | Why |
| --- | --- | --- | --- |
| 10 | [ollama/ollama](https://github.com/ollama/ollama) | 183k | Run AI models on your own computer with one command |
| 11 | [open-webui/open-webui](https://github.com/open-webui/open-webui) | 154k | A ChatGPT-style web app for your local models |
| 12 | [anthropics/claude-code](https://github.com/anthropics/claude-code) | 150k | AI coding assistant in your terminal. Great for learning to code with AI. |
| 13 | [anthropics/skills](https://github.com/anthropics/skills) | 180k | "Skills" that teach AI agents new tasks. Written mostly in plain English. |
| 14 | [n8n-io/n8n](https://github.com/n8n-io/n8n) | 207k | Drag-and-drop AI automations with little or no code |

### 🛠️ Build AI agents and apps

| # | Repo | ⭐ | Why |
| --- | --- | --- | --- |
| 15 | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | 148k | Popular framework for LLM apps and agents |
| 16 | [run-llama/llama_index](https://github.com/run-llama/llama_index) | 52k | Connect LLMs to your own documents (RAG) |
| 17 | [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) | 60k | Make teams of AI agents work together |
| 18 | [huggingface/smolagents](https://github.com/huggingface/smolagents) | 30k | Small, readable agent library, good to learn from |
| 19 | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | 91k | Official MCP server examples. Small and easy to read. |
| 20 | [browser-use/browser-use](https://github.com/browser-use/browser-use) | 118k | AI agents that use a web browser for you |

### ⚡ Star + watch them all at once

Install the [GitHub CLI](https://cli.github.com/), run `gh auth login`, then:

```bash
for r in \
  firstcontributions/first-contributions \
  microsoft/generative-ai-for-beginners microsoft/ai-agents-for-beginners \
  huggingface/agents-course microsoft/mcp-for-beginners \
  dair-ai/Prompt-Engineering-Guide f/prompts.chat \
  anthropics/claude-cookbooks openai/openai-cookbook Shubhamsaboo/awesome-llm-apps \
  ollama/ollama open-webui/open-webui anthropics/claude-code anthropics/skills n8n-io/n8n \
  langchain-ai/langchain run-llama/llama_index crewAIInc/crewAI \
  huggingface/smolagents modelcontextprotocol/servers browser-use/browser-use; do
  gh api -X PUT "user/starred/$r" --silent && echo "⭐ starred $r"
  gh api -X PUT "repos/$r/subscription" -F subscribed=true --silent && echo "👀 watching $r"
done
```

> 💡 **Watching tip:** "Watching" big repos like `claude-code` or `langchain` sends *hundreds* of emails a day.
> For most repos, choose **Watch → Custom → Releases** on the repo page instead.
> Only fully watch the 2–3 repos you want to contribute to.

---

## 🧭 How to find your first contribution

1. Finish [first-contributions](https://github.com/firstcontributions/first-contributions) to practice the fork → branch → PR flow.
2. In any repo above, open **Issues** and filter by labels like
   `good first issue`, `help wanted`, `documentation`, or `hacktoberfest` (it's October!).
3. Start with **typo fixes, docs improvements, translations, or adding a prompt/example**. These count and are welcome.
4. Leave a comment asking to work on an issue before starting.
5. Log what you did in the `contributions/` folder here.

Handy search: [good first issues in AI agent repos](https://github.com/search?q=label%3A%22good+first+issue%22+topic%3Aai-agents+state%3Aopen&type=issues)
