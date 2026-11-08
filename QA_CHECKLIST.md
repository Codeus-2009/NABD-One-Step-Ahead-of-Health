# NABD v3.7 — QA checklist before competition submission

## Automated checks
- [ ] Run `python3 tests/check_project.py`.
- [ ] Confirm the page contains no placeholder API key or secret.
- [ ] Confirm the hero image file exists beside `index.html`.

## Browser checks
- [ ] Open `index.html` in current Chrome, Edge, Firefox, and Safari where available.
- [ ] Navigate all menu links and the skip-to-content link.
- [ ] Submit each guidance path: recent/low impact, several days, persistent, and serious/worsening.
- [ ] Enter harmless fictional text in the optional note and verify it is displayed as text, not interpreted as HTML.
- [ ] Confirm urgent/serious or rapidly worsening scenarios show the caution message.
- [ ] Confirm all results are described as guidance, not diagnosis or AI analysis.
- [ ] Test on mobile and desktop; inspect the browser console for errors.

## Language checks
- [ ] Select English, Arabic, French, and Spanish; verify direction changes (Arabic RTL, others LTR).
- [ ] Check all labels, headings, result messages, buttons, help text, and accessibility states.
- [ ] Have fluent speakers review complete translations. Translation options do not mean every phrase has been professionally verified.

## Accessibility checks
- [ ] Keyboard-only navigation and visible focus.
- [ ] Text resizing, high contrast, larger targets, easy-reading mode, and reset.
- [ ] Screen-reader testing (NVDA/Firefox or Chrome; VoiceOver/Safari where available).
- [ ] Headings, labels, form errors/results, live announcements, and 200% zoom/reflow.
- [ ] Read-aloud and voice-input behavior and graceful fallbacks.

## Safety, privacy, and release
- [ ] Confirm the prototype does not claim to diagnose or provide clinical AI.
- [ ] Use fictional data only in demos; never enter real identifiers.
- [ ] Review browser speech feature behavior and privacy implications.
- [ ] Obtain qualified health-content and safeguarding review before any real-world health use.
- [ ] Complete security, privacy, dependency, and accessibility review before public deployment.
- [ ] Do not describe the prototype as clinically validated, fully accessible, error-free, or ready for medical use.

**Status:** This checklist is a plan for manual testing. Automated checks do not replace human, clinical, language, or accessibility review.
