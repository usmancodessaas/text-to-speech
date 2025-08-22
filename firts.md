

# ?? ElevenLabs TTS Clone (Frontend)

This project is a **frontend clone of the ElevenLabs Text-to-Speech interface**, built with **Next.js 14**, **TypeScript**, and **shadcn/ui**.
The goal is to replicate the UI and user flow of ElevenLabs’ text-to-speech app while staying fully customizable for future backend/API integration.

---

## ?? Tech Stack

* **Next.js 14** (App Router)
* **TypeScript** (strict mode)
* **Tailwind CSS** (utility-first styling)
* **shadcn/ui** (zinc theme for components)
* **Zustand** (lightweight state management)
* **Axios** (API calls)
* **React Hook Form + Zod** (form handling & validation)
* **Lucide React** (icons)
* **ESLint + Prettier** (code quality & formatting)

---

## ?? Project Structure

```
app/        ? Next.js routes (App Router)
components/ ? Reusable UI components
lib/        ? Utilities & helpers
store/      ? Zustand state stores
types/      ? TypeScript types & interfaces
```

---

## ?? Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/yourusername/elevenlabs-clone.git
cd elevenlabs-clone
pnpm install   # or npm install / yarn install
```

Run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## ?? Roadmap

* [ ] Core UI (text input, voice selection, play button, history sidebar)
* [ ] API integration for TTS
* [ ] User authentication
* [ ] Voice customization panel

---

## ?? License

MIT License © 2025



