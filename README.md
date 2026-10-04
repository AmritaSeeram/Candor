# Candor

**A design prototype exploring how an AI assistant can be honest about what it doesn't know.**

Most AI assistants sound equally sure whether they are right or guessing. Candor is a study planner that does three things differently:

1. **Shows confidence** as a label, a dot meter, and a sentence, never by color alone.
2. **States its assumptions** (time needed, best focus time, session length) and marks which ones you confirmed.
3. **Lets you correct it in one tap**, with undo, and raises confidence only when you confirm something.

> The prototype uses simple scripted rules so the *interaction design* can be tested with real people. It does not call a live AI model.

## Design principles

- **Honest over impressive:** confidence only rises when the user supplies information.
- **Correction is cheap:** every assumption, and every day in the plan, is one tap from fixable, and every action can be undone.
- **Accessible by default:** 44px targets, WCAG AA contrast in light and dark, a text-size control, keyboard and screen reader support (live region, labeled controls), and motion that respects reduced-motion settings.

## Run it

Open `index.html` in a browser, or publish with GitHub Pages (Settings > Pages > deploy from `main`, root folder).

## Case study: what to do next (this is the part only you can do)

The prototype is a starting point. The case study is the testing you do with it. Suggested plan:

1. Test with 5 people. Task: "Plan an essay due this week, then fix one thing the planner assumed wrong, and tell me how sure it is."
2. Record: did they notice the confidence label, did they correct an assumption, how long it took, and their trust in the suggestion (1 to 7) before and after.
3. Change something based on what you saw, and screenshot before and after.
4. Write it up: problem, research, 2 or 3 design decisions with reasons, what you changed after testing, results.

**Only report results you actually measured.**
