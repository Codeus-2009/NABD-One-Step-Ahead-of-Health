# NABD — One Step Ahead of Health

**Competition prototype | Version 3.7 | 2026**

NABD is a youth-focused health-literacy prototype that helps users organize a concern, explore basic health education, and consider a sensible next step. It prioritizes prevention, accessibility, privacy, transparency, and human oversight.

## Run locally

1. Download or clone this repository.
2. Keep `index.html` and `nabd-health-hero.png` in the same folder.
3. Open `index.html` in a current browser (Chrome, Edge, Firefox, or Safari).
4. Select a language and test the accessibility controls and guided form.

No build step, package installation, account, or API key is required for the local demo.

## What is implemented

- Responsive single-page educational website.
- English, Arabic, French, and Spanish interface options. Translation coverage is not yet fully verified; fluent human review is still required.
- Accessibility controls: text sizing, contrast, larger targets, easy-reading mode, keyboard skip link, read-aloud, and browser-supported voice input.
- A transparent, rule-based guidance demonstration with a serious/worsening concern caution path.
- Health-learning topics, healthy-habit prompts, privacy notes, and a responsible-development roadmap.
- User-entered note is displayed as text only; it is not sent to a server or processed by an AI model.

## Important technical and health limitations

- **This version does not contain a real AI model or AI API integration.** The guidance demo uses simple, inspectable rules. Do not describe it as AI-powered.
- It does not diagnose, rule out disease, recommend treatment, or replace a healthcare professional.
- Guidance rules and educational content have not been clinically validated.
- The local prototype does not transmit form responses to a server. Browser speech recognition/read-aloud may have browser or device-specific processing behavior.
- Do not enter names, addresses, contact details, or other identifying or sensitive information.
- The language selector does not mean every string has been professionally translated. Human language review is required.
- Accessibility, security, privacy, and medical-content reviews are not complete.

## Repository structure

```text
.
├── index.html
├── nabd-health-hero.png
├── README.md
├── SUBMISSION_BRIEF.md
├── DEMO_SCRIPT.md
├── QA_CHECKLIST.md
├── SECURITY.md
└── LICENSE
```

## Suggested competition demo flow

1. Introduce the problem and NABD's purpose.
2. Show the language selector and one accessibility feature.
3. Demonstrate the guided form with fictional, non-identifying inputs.
4. Show the caution path and explain that it is not a diagnosis.
5. Explain privacy-by-design and future expert review.

See [`DEMO_SCRIPT.md`](DEMO_SCRIPT.md) for a 2–3 minute narration.

## Responsible development next steps

A genuine AI feature would require a carefully scoped use case, a reviewed knowledge base, a secure server-side integration (never expose API keys in browser code), data-minimization controls, evaluation against unsafe outputs, clinical and safeguarding review, and clear human escalation. Do not add an AI model merely to label the project as AI.

## License

The source code is provided under the MIT License. The bundled image may have separate rights; confirm its provenance and permission before public redistribution.
