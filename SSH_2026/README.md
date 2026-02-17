# Interactive Multimodal AI Buddy

**An AI Companion for Real-Time Emotion-Aware Conversations**

A **desktop application** built with **Electron + React** frontend and **Python FastAPI** backend, providing an intelligent, multimodal AI companion with facial recognition, voice interaction, real-time vision understanding, and personalized long-term memory.

---

## 🚀 Overview

The **Interactive Multimodal AI Buddy** is an advanced AI companion designed to engage users in real-time, emotionally intelligent conversations. By integrating multimodal inputs—voice, facial expressions, and live camera vision—the system adapts its responses based on the user's emotional state and visual context, fostering natural and empathetic interactions.

This is a **desktop application** built with modern web technologies (Electron + React) for the UI and Python for AI processing, featuring a **dual-socket architecture** that separates real-time audio streaming from cognitive reasoning.

---

## 🚀 Development

### Run in Development Mode
```bash
cd frontend
npm run dev
```
This starts:
- Python FastAPI backend on `http://127.0.0.1:8000`
- Vite dev server on `http://localhost:5173`
- Opens in your browser (use `npm run dev:electron` for Electron window)

### Available Scripts
| Script | Description |
|--------|-------------|
| `npm run dev` | Start backend + frontend concurrently |
| `npm run dev:electron` | Launch Electron desktop window |
| `npm run build:electron` | Build distributable desktop app |
| `npm run typecheck` | TypeScript type checking |
| `npm run lint` | ESLint code linting |
| `npm run format` | Prettier code formatting |

### Build for Production
```bash
cd frontend
npm run build:electron
```
Creates a distributable desktop app in `frontend/release/` directory.

---


