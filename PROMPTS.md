# Prompt Documentation – VisitReady

**AI tool used:** Claude (Anthropic) – chosen for strong code generation, long-context understanding of the assessment brief, and ability to create and edit files directly.

## Prompt 1 – Initial prompt (actual)
I pasted the full assessment brief (Task 1: AI Skills & Prompt Engineering Assessment, Gokul Infocare) and wrote:

> "Mala ha simple project banvun de, hyat jas sangitaly tas."
> (Build me a simple project for this, as described in the brief.)

**Why this worked:** giving the complete brief as context let the AI pick a suitable domain (Healthcare), choose one area (Website Development), keep scope simple, and prepare all 3 submission items.

**Result:** VisitReady, a single-file web app plus README and this document.

---

## Follow-up prompts (add YOUR real ones here)
Replace the examples below with the exact prompts you actually use when refining. Evaluators want to see your genuine iterations.

### Prompt 2 – Refinement (example template)
> "Add a severity slider and a red-flag warning when the user selects chest pain or shortness of breath."

**Why:** safety – the app should never encourage waiting when symptoms may be serious.

### Prompt 3 – UX / mobile (example template)
> "Make the layout mobile-friendly and add a Print / Save as PDF button that hides the form."

### Prompt 4 – Content quality (example template)
> "Add condition-specific questions for fever, cough, rash and fatigue, and a 'what to bring' checklist."

### Prompt 5 – Debugging (example template)
> "The copy button does nothing on Safari. Add a fallback and explain the cause."

---

## Prompt-engineering approach (for your video)
1. **Context first:** gave the full brief instead of a one-line idea.
2. **Constraints:** simple, single-file, no backend, privacy-friendly.
3. **Safety by design:** disclaimer plus red-flag logic for a healthcare app.
4. **Iterate in small steps:** one feature per follow-up prompt, test, then refine.
5. **Verify:** test the output in a browser, then fix issues through targeted prompts.
