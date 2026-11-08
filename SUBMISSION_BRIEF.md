# NABD — One Step Ahead of Health
## Competition submission brief — Prototype v3.7

### Project summary
NABD is a youth-focused digital health-literacy prototype. It helps users organize a concern, access introductory health education, and consider an appropriate next step. Its central principle is that health awareness and prevention should begin before a concern becomes serious, while professional care remains essential.

### Problem
People can struggle to turn a health concern into a clear next step. Young users and people with accessibility needs may face additional barriers when health information is complex, difficult to navigate, or unavailable in a readable format.

### Solution
NABD combines guided reflection, accessible educational content, healthy-habit prompts, multilingual interface options, and transparent safety messaging in one responsive website.

### Current working features
- Responsive single-page web prototype.
- English, Arabic, French, and Spanish language options; full translation coverage still needs fluent human review.
- Accessibility controls for text size, contrast, target size, simplified reading, keyboard navigation, read-aloud, and supported voice input.
- Rule-based demonstration flow using duration, impact, and a user-selected serious/worsening flag.
- A user note can be shown back to the user; it is not sent to a server or interpreted by an AI model.
- Learning topics, healthy-habit information, privacy notes, and a development roadmap.

### Technical honesty
**The current prototype is not powered by a real AI model.** The guidance logic is a small transparent rule-based demonstration. It must not be presented as AI diagnosis or clinical decision support. A future AI integration would require secure server-side credentials, a narrow educational scope, reviewed sources, evaluation, safeguards, and qualified oversight.

### Safety and privacy
NABD does not diagnose, rule out disease, prescribe treatment, or replace healthcare professionals. It is not clinically validated. The local demo does not send form responses to a server and has no user accounts, advertising trackers, or external analytics. Browser speech features may have their own processing behavior. Users should not enter identifying or sensitive personal information. Urgent or rapidly worsening concerns should be directed to appropriate local professional or emergency services.

### Intended users
The concept is designed for a broad audience, with particular attention to young people and users who benefit from larger text, high contrast, keyboard navigation, simplified reading, or read-aloud support.

### Impact and evaluation plan
A future pilot could measure:
- Whether users understand that the tool is educational and not diagnostic.
- Whether users can find safety information and appropriate escalation guidance.
- Task completion on mobile and desktop.
- Accessibility issues found through assistive-technology testing.
- Translation accuracy and comprehension reviewed by fluent speakers.
- User-reported clarity, without collecting unnecessary health identifiers.

### Next development steps
1. Complete human review of translations and health education content.
2. Test with keyboard-only navigation, screen readers, magnification, and users with varied access needs.
3. Obtain qualified clinical and safeguarding review of all health-related content and safety rules.
4. Complete privacy, security, and dependency assessment before deployment.
5. Consider a narrowly scoped AI educational assistant only after a secure architecture and evaluation plan are approved.

### Competition submission checklist
- Publish the source repository and verify that the image asset is included.
- Record a 2–3 minute screen-only demo; no face is needed unless the organizer separately requires it.
- Include a clear project description, limitations, and the fact that this prototype does not use real AI.
- Use fictional demonstration inputs only.
