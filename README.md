I love using Ollama, but I found myself constantly missing a lightweight, local desktop manager to quickly check my downloaded models, adjust context lengths on the fly, and cleanly manage the background server.

So, I built Ollama Manager — a standalone Windows desktop app designed to give you full control over your local LLM workflow without any heavy dependencies.

Since it's completely compiled, you don't need Python or anything else installed. Just download the .exe and run it alongside Ollama.

🚀 Key Features
⚡ Auto & Deep Boost (The VRAM Lifesaver): One of my biggest pet peeves was models staying loaded in memory when I needed my GPU for gaming or other tasks. The app features a one-click or automated "Deep Boost" that forces model unloads, trims working sets, and flushes the Windows standby cache to free up RAM/VRAM instantly.

📦 Complete Online Model Library: Browse the entire Ollama library directly inside the app. It caches popular models, parses their context capabilities (Text, Vision, Tools, Thinking), and lets you download specific quantizations/sizes with a detailed progress bar (showing speed, percentage, and ETA).

🔧 On-the-Fly Parameter Tuning: Quickly adjust critical settings before launching a model:

Context length (num_ctx)

Keep-alive timeout (keep_alive)

CPU threads, GPU layers, batch sizes, Flash Attention, and Temperature.

💬 Integrated Streaming Chat: Includes a clean, local chat interface that perfectly isolates <think> blocks for reasoning models (like DeepSeek-R1) so you can toggle thinking visibility on or off.

🧩 Codex App Integration: Dedicated commands to launch your local models straight into the Codex App ecosystem or restore configurations with a single click.

🛠️ No Setup Required
It looks for your standard ollama executable in your PATH, reads your existing environment variables (like OLLAMA_MODELS), and lets you change or clear custom model directory paths directly through the UI.

📥 Download

Note: This is a compiled standalone tool designed strictly for Windows environments to streamline local model maintenance.

Curious to hear your thoughts! What features should I add next?
