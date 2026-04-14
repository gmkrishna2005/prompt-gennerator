# PromptForge - Intelligent Prompt Generator

Transform plain text into optimized, structured AI prompts instantly without needing any API keys. PromptForge uses a powerful client-side intent detection engine to analyze your requirements and automatically applies the best prompt engineering techniques.

## ✨ Features

- **100% Client-Side Detection:** Runs entirely in your browser. No data is sent anywhere, and no API keys are required.
- **Smart Intent Recognition:** Analyzes your text using intelligent keyword matching to understand your underlying goal.
- **Auto-Technique Selection:** Matches your intent to proven prompting styles (Zero-Shot, Few-Shot, Chain-of-Thought, Role Prompting, etc.).
- **Structured Output:** Automatically structures the final prompt with Role, Context, Task, Tone, and Constraints.
- **Premium UI:** Beautiful, modern interface with glassmorphism, animated thinking steps, and live real-time detection.

## 🚀 How It Works

PromptForge bridges the gap between a rough idea and a production-ready AI prompt through a customized 4-step pipeline:

1. **Parsing Input:** It reads your initial, plain text idea (e.g., "give me startup ideas for students").
2. **Intent Detection:** The internal engine scores the text against multiple intent categories (Creative Ideation, Problem Solving, Procedural, Expert Advice, etc.) based on keywords.
3. **Technique Mapping:** Depending on the detected intent, it selects optimal techniques (e.g., Explorative + Few-Shot + Role Prompting).
4. **Prompt Generation:** It compiles a structured prompt using tailored templates for a specific Role, comprehensive Context, detailed Task instructions, appropriate Tone, and bounding Constraints.

## 🔑 How It Generates Prompts WITHOUT an API Key

Unlike many prompt generators that send your text to an LLM for formatting, PromptForge includes its own **built-in algorithmic engine**:

- **Local Pattern Matching:** The logic uses carefully crafted keyword heuristics to determine what you're trying to achieve. 
- **Template Architecture:** It applies internal knowledge of prompt engineering best practices directly via JavaScript templates without external processing.
- **Instantaneous Generation:** Because there are no network requests or external dependencies, generating the prompt is both instant and completely private.

## 💻 Usage

Simply open `prompt-converter.html` in any modern web browser to start using PromptForge immediately!

1. Type your idea into the text box.
2. Observe the live intent detector identifying your objective.
3. Generate the Prompt.
4. Copy individual sections or the entire prompt to use in ChatGPT, Claude, Gemini, or any other AI tool.