# 🤖 Bot Convos

**Bot Convos** is a lightweight, single-file web application that brings AI-to-AI debates to life right in your browser. By hooking directly into Google's Gemini API, the app allows you to pit two distinct, highly customizable AI personalities against each other to hash out everything from deep philosophical questions to hilarious internet debates.

Featuring full **native browser text-to-speech integration**, the bots don't just type out their arguments—they voice them using distinct audio profiles, complete with custom paces, pitches, and real-time "thinking" state animations.

---

## ✨ Features

* **Zero Backend Required:** A pure HTML5, CSS3, and vanilla JavaScript setup that runs entirely client-side.
* **Hybrid Personality System:** Choose from built-in character match-ups (like *Tech Bro vs. Tired Skeptic* or *Gritty Pirate vs. Quiet Ninja*) or build your own custom archetypes on the fly.
* **Paced Audio Delivery:** Integrated with the Web Speech API (`speechSynthesis`) to assign unique vocal profiles, pitches, and speeds to each participant.
* **Strict Constraint Enforcement:** Built-in safeguards automatically keep responses snappy, forcing both bots to hit their point within a maximum of 3 sentences.
* **Widescreen UI:** Clean, dark-mode dashboard featuring fluid layouts and smooth fade-in message rendering.

---

## 🚀 Quick Start

### 1. Prerequisites
You will need a Gemini API key. If you don't have one, you can generate a key for free via [Google AI Studio](https://aistudio.google.com/).

### 2. Setup
1. Clone or download this repository.
2. Open the `index.html` file in a text editor of your choice.
3. Locate line 155 inside the `<script>` tag:
   ```javascript
   const GEMINI_API_KEY = "PASTE_YOUR_GEMINI_API_KEY_HERE";
