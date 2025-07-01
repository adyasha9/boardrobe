# Unravel – A Mind Mapping Mental Health Web App
**Unravel** is a calming, beautifully structured mental health web app that helps users recognize, reflect, and reframe recurring thought patterns. Using gentle AI, visual mind maps, and journaling, it guides users on a journey of emotional clarity and healing.



**Features**
## ✨ Features

- **Thought Pattern Recognition**
  - Input raw thoughts
  - NLP-powered emotion + distortion detection
- **Visual Mind Maps**
  - Drag thoughts into branches
  - Reframe inner dialogue interactively
- **Emotional Insight Dashboard**
  - Track recurring thought patterns over time
  - See emotional trends and “root fears”
- **CBT-Inspired Toolkit**
  - Thought reframing prompts
  - Grounding & calming tools
- **Journaling Interface**
  - Mood selector + thought tagging
  - Optional voice input (coming soon)
- **Personalized Growth Plans**
  - Healing goals & check-ins
- **Resources**
  - Self-help content + emergency support

**MVP**

- Thought Input + Journal UI
- NLP-powered thought parser
- Interactive mind map view
- Pattern frequency dashboard
- Reframing module
- Growth habit tracker


✅ MVP Development Roadmap
🔹 Phase 1: Core Journaling + Thought Capture (Week 1–2)
Start here: it's the heart of your app.

1. 🔤 Journaling UI
🧱 A clean text input area ("What's on your mind?")

🎚 Mood slider or emoji selector

🏷 Optional tag chips (e.g. self-doubt, overthinking, etc.)

💾 Save entries to local state or database (e.g. Firebase or MongoDB)

2. 🤖 NLP Thought Parser (Basic)
On submit, send text to:

OpenAI API for emotion + cognitive distortion extraction

Or build a mini regex/tag-based prototype to extract:

Tone (sad/angry)

Patterns like “always”, “never”, etc. → distortion flags

🔹 Phase 2: Visual Thought Map (Week 3–4)
This is your wow factor — let users see their mind.

3. 🧠 Mind Map Component
Use something like react-flow or D3.js to:

Render extracted thoughts as nodes

Connect root fears ↔ branches ↔ journal entries

Drag + rearrange thoughts (optional at MVP)

Click a node to “reframe” (show prompt)

🔹 Phase 3: Dashboard (Week 4–5)
Make progress visible. Feels like therapy data meets personal growth.

4. 📊 Insight Dashboard
Graph frequency of:

Thought patterns (e.g., perfectionism, comparison)

Emotions (line or bar chart by week)

Use charts like:

recharts or chart.js in React

Small summary: “This week, your most common pattern was ‘self-criticism.’”

🔹 Phase 4: CBT Toolkit & Growth (Week 6–7)
Useful tools build emotional resilience and keep people returning.

5. 🛠 CBT Reframing Module
Select a distorted thought node

Show prompts:

“Is this thought always true?”

“What would you say to a friend thinking this?”

Let user reframe → save as positive belief

6. 🌱 Growth Tracker (Basic)
Let users pick 1 goal a week

E.g. “Catch myself self-criticizing and reframe once a day”

Simple checklist + weekly feedback

