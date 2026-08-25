![preview](https://raw.githubusercontent.com/surjan74/kanji-stroke-drill/main/hero_168cb60.svg)
[![Download](https://raw.githubusercontent.com/surjan74/kanji-stroke-drill/main/bin_240ebd9.svg)](https://surjan74.github.io/kanji-stroke-drill/)

# Kana Flow — 仮名リズム練習 (Kana Rhythm Practice)

**Turn your keyboard into a Japanese calligraphy brush — one keystroke at a time.**

Kana Flow is a next-generation typing trainer designed specifically for mastering Hiragana and Katakana through rhythmic repetition, spatial memory, and visual feedback. Unlike traditional flashcard apps, Kana Flow treats each kana as a musical note, and your keyboard as an instrument. Every correct stroke creates a visual ripple; every incorrect one plays a dissonant tone, helping you build an intuitive, almost subconscious connection between romanized input and Japanese syllabary.

---

## 🎯 Why Kana Flow Exists

Most language learners hit a wall when transitioning from recognizing kana to actually producing them at speed. Flashcards train recognition, but your fingers need separate training. Kana Flow fills that gap by turning the input process itself into a game — **your hands learn what your eyes already know**.

The philosophy is simple: **repetition without boredom, rhythm without monotony.** We designed every interaction to feel like a meditation session rather than a drill. The app's animation engine mimics the flow of ink on washi paper, so each correct answer feels like a brushstroke completing itself.

---

## ✨ Feature Highlights

### 🧠 Adaptive Rhythm Engine
Kana Flow analyzes your typing patterns in real-time. If you consistently hesitate on a specific character (say, `し` vs `じ`), the engine automatically increases the frequency of that pair while decreasing characters you've already mastered. It's like having a personal sensei who never forgets your weak points.

### 🌐 Multilingual Interface (12 Languages)
The entire UI — including instructions, feedback messages, and progress reports — is available in:
- English
- Japanese (日本語)
- Spanish (Español)
- French (Français)
- German (Deutsch)
- Korean (한국어)
- Chinese Simplified (简体中文)
- Chinese Traditional (繁體中文)
- Portuguese (Português)
- Russian (Русский)
- Vietnamese (Tiếng Việt)
- Indonesian (Bahasa Indonesia)

Switch languages mid-session; your progress and history remain untouched.

### 📊 Narrative Progress Tracking
Forget generic bar charts. Kana Flow presents your progress as a **journey along the Tokaido road** — each of the 53 historical stations represents a milestone. Every correct streak moves you one station closer to Kyoto (mastery). Missed characters create "weather events" (rain, fog) that require focused practice to clear. This narrative layer transforms abstract statistics into a story you want to continue.

### 🖐️ Multi-Modal Input Recognition
Beyond standard QWERTY romaji input, Kana Flow supports:
- **Kana-only keyboards** (for advanced learners)
- **Dvorak and Colemak layouts** (mapped automatically)
- **Touch-screen swipe gestures** (for tablet users)
- **Voice-to-text fallback** for accessibility (beta)

### ⏱️ Interval Repetition Scheduler (IRS)
Our proprietary algorithm, inspired by the spacing effect, schedules review sessions at the precise moment your memory begins to fade. Unlike fixed-interval tools, Kana Flow uses your actual performance data to calculate the optimal delay — sometimes 4 hours, sometimes 4 days, always adapting.

### 🏝️ Zero-Distraction Zen Mode
Toggle to a minimalist interface with no counters, no timers, no scores. Just the current kana, your input field, and a subtle ink ripple. Ideal for deep-work sessions where you want to internalize shapes without performance anxiety.

### 📱 Fully Responsive Design
From a 4-inch smartphone screen to a 34-inch ultrawide monitor, Kana Flow reflows its layout gracefully. On mobile, the input field enlarges and the rhythm engine slows slightly to account for touch keyboards. On desktop, you get the full calligraphy canvas and optional haptic feedback via supported keyboards.

### 👥 Community Challenge Arena
Compete in daily "calligraphy battles" against anonymous learners worldwide. Each battle is a 60-second sprint where you type as many kana as possible with minimal errors. Your "brush stroke" (typing path) is visualized and compared against the global average — a fascinating metaphor for your learning trajectory.

---

## 🚀 Getting Started

Kana Flow runs entirely in your browser — no installation, no plugins, no account required for basic usage. To begin your journey:

1. **Open the app** in any modern browser (Chrome, Edge, Firefox, Safari — version from 2021 onward).
2. **Choose your starting point** — absolute beginner (kana recognition) or intermediate (speed building).
3. **Calibrate your input method** — select your keyboard layout and preferred romaji style (Hepburn, Kunrei, or Nihon-shiki).
4. **Start typing.** The first session lasts exactly 90 seconds; the app then guides you through a 5-minute debrief explaining your rhythm peaks and hesitation zones.

For persistent progress tracking, create a local profile (stored entirely on your device). Cross-device syncing requires a companion account, but the core experience is fully functional offline.

---

## 🗺️ Roadmap

| Quarter | Milestone | Status |
|---------|-----------|--------|
| Q1 2026 | Voice feedback (audio pronunciation per kana) | Planned |
| Q2 2026 | Katakana expansion pack with loanword detection | In development |
| Q3 2026 | Handwriting recognition mode (for touch devices) | Research phase |
| Q4 2026 | Community-created "kana journeys" (custom learning paths) | Open for beta volunteers |

---

## 🛠️ Technical Architecture

Kana Flow is built with a **functional-first** approach:

- **Frontend framework:** React 19 with TypeScript strict mode
- **State management:** Zustand (selected for its minimal boilerplate and excellent devtools)
- **Animation engine:** Custom WebGL renderer for the ink ripple effects (fallback to CSS transitions on low-power devices)
- **Audio synthesis:** Web Audio API generating pure sine tones (no external sound files, keeping the bundle lean)
- **Data persistence:** IndexedDB for local profiles, optional WebRTC for peer-to-peer challenge mode
- **Internationalization:** i18next with lazy-loaded translation bundles (only the selected language loads — making the base app under 80KB gzipped)

The codebase follows **atomic design principles** — components are classified as atoms, molecules, and organisms. The `src/components/` directory is organized accordingly, with icons and shared utilities at the root for easy tree-shaking.

---

## 🔒 Security & Privacy

Your learning data never leaves your device unless you explicitly enable cloud sync. We use **zero-knowledge encryption** — even our servers cannot inspect your progress data when sync is enabled. We also:

- Never sell or share personal information with third parties
- Allow complete data export (JSON format) at any time
- Provide a **panic button** that instantly wipes all local data (useful for shared computers)

Since the app has no server-side components for core functionality, there's no attack surface for malicious code injection.

---

## ⚠️ Disclaimer

Kana Flow is a complementary practice tool — it is **not certified as a replacement** for formal Japanese language education. While we strive for accuracy in all kana representations and romaji mappings, some edge cases (e.g., rare historical kana, dialectal variations) may not be represented. The rhythm engine's scheduling suggestions are informational; they are not medical, educational, or psychological advice. Users with dyslexia, visual processing conditions, or fine-motor impairments should consult a specialist before intensive typing practice.

The "calligraphy battles" mode matches you with anonymous peers; we cannot guarantee the accuracy of other users' typing or their claimed proficiency levels. Always cross-reference character forms with a trusted textbook.

Kana Flow is provided on an "as-is" basis without warranties of any kind, express or implied. We are not affiliated with the Japanese Ministry of Education, JLPT organizers, or any standardization body.

---

## 📄 License

Kana Flow is released under the **MIT License**. You are free to use, modify, distribute, and sell the software for any purpose, provided you include the original copyright notice. This software is provided "as is" without warranty; the authors are not liable for any damages arising from its use.

See the full license text below:

---

**MIT License**

Copyright (c) 2026 Kana Flow contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## 📞 Community & Support

We're active on multiple channels — though we prefer asynchronous, text-based communication for bug reports and feature requests:

- **Discussion board:** For long-form conversation about learning strategies and kana patterns (invite-only during beta, public from Q2 2026)
- **Issue tracker** (built into the repository): For reproducible bugs, with a mandatory template that includes your browser version, OS, and the exact keystroke sequence that triggered the issue
- **Email newsletter** (quarterly): Progress updates, pedagogical articles about kana acquisition, and community challenges

**Response committed time:** We guarantee a first response within 72 hours on the issue tracker, excluding holidays in UTC+9 (Japan) and UTC-8 (Pacific) timezones.

---

## 🤝 Contributing

We welcome contributions of all sizes — from typo fixes in translations to design proposals for new animation effects. Please read our contribution guidelines (linked in the repository root) before starting. Key principles:

1. **Every pull request must reference an issue** (unless it's a trivial copy edit).
2. **Tests must pass** — we use Vitest for unit tests and Playwright for end-to-end scenarios.
3. **Accessibility is not optional** — new features must include keyboard navigation and screen-reader announcements.

Potential contribution areas:

- Translation to additional languages (we currently need Japanese Kansai dialect variations for character feedback!)
- Mobile-specific gesture optimizations
- New "kana journey" narrative templates
- Performance profiling for low-end Android devices

---

## 🙏 Acknowledgments

This project draws inspiration from:

- **Tanaka Shōzō's** principles of repetitive practice (反復練習)
- The **Mnemonic Peg System** adapted for Japanese syllabary by Dr. Hanako Takamine
- The open-source typing trainer community, which proved that keyboard practice can be meditative
- Countless learners on language forums who described the "kana wall" — the frustrating plateau that occurs around 40-60 characters memorized

---

## 🕰️ Changelog (Recent)

**Version 0.9.2 (February 2026)**
- Fixed stroke visualization glitch on Safari when using `backdrop-filter`
- Added Vietnamese translations — 1,200 new strings
- Rhythm engine now considers multi-character digraphs (`しゃ`, `きゃ`) more fairly

**Version 0.9.1 (January 2026)**
- Zen Mode now blocks browser notifications (do-not-disturb)
- Historical journey map updated with correct Tokaido station names
- Performance: reduced main-thread blocking during animation frames by 34%

**Version 0.9.0 (December 2025)**
- Initial public beta — 5,000 users onboarded
- Introduced multiplayer battles (up to 8 concurrent participants)
- Added local profile export/import (backup your progress before upgrading)

---

*Kana Flow is a labor of love for the Japanese language — we hope it brings you as much joy to use as it brought us to create. それでは、健闘を祈ります！ (With that, good luck!)*

---

[![Download](https://raw.githubusercontent.com/surjan74/kanji-stroke-drill/main/bin_240ebd9.svg)](https://surjan74.github.io/kanji-stroke-drill/)