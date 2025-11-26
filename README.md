# 🧠 MindBridge  
A relaxed little AI brain that rebuilds context from what it knows about you.

MindBridge isn’t a chatbot. It’s a **context engine**.  
It takes your stored data — resume, last prompts, preferences, personality notes —  
and **reconstructs a clean, fresh context** for every LLM call. No clutter. No endless history.  
Just refined, structured prompts, every time.

I built this to experiment with AI memory, refine responses, and explore how far context  
can go when it’s rebuilt instead of stacked.

---

## 🌿 What MindBridge Does
- Stores user data (resume, preferences, last prompt, metadata)
- Rebuilds conversation context from scratch for each request  
- Refines prompts before sending them to an LLM  
- Acts as a clean gateway between the DB, the user, and the model  
- Keeps everything simple, predictable, and fun to tweak

---

## 🚀 Tech
**Backend**
- .NET API  
- Database via EF Core  
- Connects to local or remote LLMs  

**Frontend**
- Svelte  
- A small, reactive UI for testing conversations and context
---
