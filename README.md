# TAG AI Literacy

**A comprehensive educational resource for understanding artificial intelligence.**

[![Live Site](https://img.shields.io/badge/Live%20Site-GitHub%20Pages-blue)](https://theapiguysdev.github.io/tag-ai-literacy/)
[![Built with MkDocs](https://img.shields.io/badge/Built%20with-MkDocs-526CFE)](https://www.mkdocs.org/)

---

## 🎯 About

The TAG AI Literacy project provides a comprehensive, accessible resource to help people understand artificial intelligence. Whether you're a business leader evaluating AI solutions, a developer building AI-powered applications, or simply curious about AI's impact on society, this resource offers clear, jargon-free explanations of AI concepts.

**Visit the live site:** [theapiguysdev.github.io/tag-ai-literacy](https://theapiguysdev.github.io/tag-ai-literacy/)

---

## 📚 What's Included

### 🔤 [AI Glossary](https://theapiguysdev.github.io/tag-ai-literacy/glossary/)
Top 10 essential AI terms with clear definitions, real-world examples, and practical context:
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Large Language Model (LLM)
- Natural Language Processing (NLP)
- Deep Learning
- Neural Network
- Training Data
- Prompt
- Fine-tuning
- Hallucination

### ⚖️ [Benefits and Risks](https://theapiguysdev.github.io/tag-ai-literacy/benefits-and-risks/)
A balanced view of AI's impact with 8 major benefits and 10 key risks:
- **Benefits:** Productivity, accessibility, problem-solving, and more
- **Risks:** Bias, privacy concerns, misinformation, job displacement, and more
- Real-world examples and mitigation strategies for each

### 🛠️ [Products & Services](https://theapiguysdev.github.io/tag-ai-literacy/products-services/)
Comprehensive overview of 18+ AI tools organized by category:
- Conversational AI & LLMs (Claude, ChatGPT, Gemini, Microsoft Copilot)
- AI Coding Assistants (GitHub Copilot, Cursor, Replit, Codeium)
- Image Generation (Midjourney, DALL-E 3, Adobe Firefly, Stable Diffusion)
- Video & Audio AI (Runway ML, ElevenLabs)
- AI Search & Research (Perplexity AI, Notion AI)
- Specialized Tools (Grammarly, Jasper AI)

### 📅 [AI Timeline](https://theapiguysdev.github.io/tag-ai-literacy/timeline/)
Key milestones in AI history from 1950 to 2026:
- Foundational concepts (Turing Test, Dartmouth Conference)
- Major breakthroughs (Deep Blue, AlphaGo, AlphaFold)
- Modern era (GPT series, Claude, Gemini, and more)

---

## 🚀 Local Development

### Prerequisites

```bash
pip install mkdocs mkdocs-material
```

### Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TheAPIGuysDev/tag-ai-literacy.git
   cd tag-ai-literacy
   ```

2. **Navigate to the documentation directory:**
   ```bash
   cd claude
   ```

3. **Start the development server:**
   ```bash
   mkdocs serve
   ```

4. **Open in your browser:**
   ```
   http://127.0.0.1:8000
   ```

The site will auto-reload when you edit markdown files!

### Build Static Site

```bash
cd claude
mkdocs build
```

The built site will be in the `site/` directory.

---

## 📝 Contributing

### Adding Content

1. **Edit existing pages** in `claude/docs/`:
   - `glossary.md` - AI terminology
   - `benefits-and-risks.md` - AI impacts
   - `products-services.md` - AI tools and services
   - `timeline.md` - AI history

2. **Add new pages:**
   - Create a new `.md` file in `claude/docs/`
   - Add it to the `nav` section in `claude/mkdocs.yml`

3. **Test locally:**
   ```bash
   cd claude
   mkdocs serve
   ```

4. **Deploy to GitHub Pages:**
   ```bash
   cd claude
   mkdocs gh-deploy
   ```

### Markdown Features

The documentation supports:
- **Admonitions** - Info boxes, tips, warnings
- **Code highlighting** - Syntax highlighting for multiple languages
- **Tables** - Markdown tables
- **Task lists** - Checkboxes for tasks

---

## 🎨 Project Structure

```
tag-ai-literacy/
├── README.md              # This file
├── CLAUDE.md             # Guidance for Claude Code
├── .gitignore            # Git ignore rules
└── claude/               # MkDocs documentation
    ├── mkdocs.yml        # MkDocs configuration
    ├── README.md         # Documentation usage guide
    └── docs/             # Content pages
        ├── index.md                  # Home page
        ├── glossary.md               # AI terminology
        ├── benefits-and-risks.md     # AI impacts
        ├── products-services.md      # AI tools
        └── timeline.md               # AI history
```

---

## 🎯 Mission

Our goals are to:
- **Clarify** complex AI terminology into understandable language
- **Educate** on both capabilities and limitations of AI technologies
- **Elucidate** real-world benefits, risks, and ethical considerations
- **Empower** informed decision-making about AI adoption and usage
- **Build** a foundation for AI literacy that grows with the technology

This is a living resource that evolves as AI technology advances, ensuring content remains relevant and practical.

---

## 📖 Resources

- **Live Site:** [theapiguysdev.github.io/tag-ai-literacy](https://theapiguysdev.github.io/tag-ai-literacy/)
- **MkDocs:** [mkdocs.org](https://www.mkdocs.org/)
- **Repository:** [github.com/TheAPIGuysDev/tag-ai-literacy](https://github.com/TheAPIGuysDev/tag-ai-literacy)

---

## 📄 License

This project is maintained by [The API Guys](https://github.com/TheAPIGuysDev).

---

**Making AI literacy accessible to everyone.** 🤖✨
