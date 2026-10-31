# CodeLens Prototype

**Tagline:** Pause. Read. Understand.

## Problem
Beginners often copy code without understanding why each line is written. This makes it harder to debug, modify, and learn programming independently.

## Solution
CodeLens is a simple browser-based learning prototype. A user pastes a short code sample and receives beginner-friendly, line-by-line explanations for common Python and C patterns.

## Run the prototype
1. Extract `CodeLens_Source.zip`.
2. Open `index.html` in Chrome, Edge, or another modern browser.
3. Paste a small code sample and click **Explain my code**.
4. Try **Load example**, edit a line, and explain it again.

No installation, account, or internet connection is required.

## Current scope and limitations
- Demonstrates common beginner-level code patterns.
- Uses rule-based explanations; it does not run the submitted code.
- It is not a full AI code debugger and may give general explanations for unfamiliar syntax.
- Future improvements could include more languages, safer syntax-aware parsing, examples, and an AI explanation service.

## Suggested demo
Show the default Python example, click Explain my code, then change `number = 5` to `number = -2` and explain it again. Explain that the prototype focuses on understanding code rather than simply copying an answer.
