# Adaptive Learning Demo

An interactive web-based demonstration of AI-driven adaptive learning, presenting educational content on prompt engineering techniques across six distinct learning style modalities.

**Live Demo:** [https://archiecur.github.io/adaptive_learning_demo/](https://archiecur.github.io/adaptive_learning_demo/)

---

## Overview

The Adaptive Learning Demo is a proof-of-concept application that illustrates how a single body of educational material can be dynamically restructured and presented to accommodate diverse learner preferences. The application delivers instruction on the *Copilot Prompt Toolkit* — a set of six techniques for communicating effectively with AI assistants — reformatted for six evidence-based learning profiles.

This project sits at the intersection of adaptive learning systems, AI literacy education, and instructional design research. It demonstrates that meaningful personalization of educational content does not require complex backend infrastructure; the adaptation logic is entirely client-side.

---

## Educational Content: The Copilot Prompt Toolkit

The application teaches the following AI prompt engineering techniques:

| Technique | Description |
|---|---|
| Adopting Personas | Assigning specialized roles to the AI to access domain-specific knowledge |
| Collaborative Questioning | Requesting AI assistance in scoping and defining requirements |
| Iterative Refinement | Incrementally sculpting AI outputs through successive prompts |
| Human Verification | Critically validating and fact-checking AI-generated content |
| Meta-Prompting | Using prompts that govern or improve the prompting process itself |
| Strategic Trait Combinations | Integrating multiple techniques for enhanced output quality |

---

## Learning Style Modalities

Content is adapted and presented across six learner profiles:

- **Visual** — Concept maps, diagrams, and structured visual representations
- **Auditory** — Narration placeholders and verbal explanation formats
- **Read-Write** — Text-dense presentations with note-taking activities
- **Kinesthetic** — Hands-on interactive exercises and prompt-building tools
- **Sequential** — Step-by-step structured progressions
- **Global** — Big-picture overviews preceding detail-level instruction

---

## Repository Structure

```
adaptive_learning_demo/
├── index.html                                  # Main interactive application
├── README.md                                   # This file
├── AI Learning Style Adaptation-Claude.docx   # Content adaptation guide
├── Future work-Real-Time Behavioral Analytics3.docx  # Research extension notes
├── Learning_Preferences_Intake_Form.docx       # Learner self-assessment instrument
└── Systematic_Literature_Review.pdf            # Supporting literature review
```

---

## Technical Implementation

The application is implemented as a self-contained single-page application with no external dependencies.

- **Stack:** HTML5, CSS3, vanilla JavaScript
- **Architecture:** Client-side only; no server, build process, or package manager required
- **Deployment:** Compatible with any static web host, including GitHub Pages

Key implementation details:

- Profile selection triggers dynamic show/hide of content sections via JavaScript
- Layout uses CSS Grid and Flexbox for responsive rendering
- Interactive elements include prompt generators, copy-to-clipboard utilities, textarea inputs, and audio controls
- All styling and logic is embedded within `index.html`

---

## Usage

### Running Locally

1. Clone or download the repository:
   ```bash
   git clone https://github.com/ArchieCur/adaptive_learning_demo.git
   ```
2. Open `index.html` in any modern web browser.

No installation, build step, or internet connection is required.

### Using the Application

1. On load, select a learner profile from the six profile cards displayed at the top of the page.
2. The content area updates to present the Copilot Prompt Toolkit material in the format optimized for that profile.
3. Engage with profile-specific interactive elements (prompt builders, exercises, note fields, audio controls) as presented.

---

## Research Context

This project is accompanied by a *Systematic Literature Review* (included in the repository) that establishes the theoretical basis for the learning style categories employed. The supporting documentation addresses:

- The rationale for multi-modal content adaptation in AI literacy instruction
- A learner intake instrument for identifying individual learning preferences
- Notes on potential extensions involving real-time behavioral analytics

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## Credits

Developed by **ArchieCur** with content adaptation and instructional design assistance from **Claude Sonnet 4.0** (Anthropic).
