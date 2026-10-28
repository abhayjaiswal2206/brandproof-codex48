# BrandProof

BrandProof is a Codex 48 prototype for checking advertisement claims against approved product facts before publication.

## Current MVP

- Approved product facts as a source of truth
- Advertisement text review
- Evidence-linked findings for contradictory and unsupported claims
- Suggested corrections that preserve the creator's intent
- Human approval or send-back decision
- Local audit history

## Run locally

Open `index.html` in a browser. No installation or API key is required for this first prototype.

## Important disclosure

This first prototype uses deterministic checks in the browser so that the demo works reliably without an external AI key. For the hackathon build, the review engine can be replaced or extended with a hosted LLM that returns schema-validated findings. Any AI tools, models, libraries, and external services must be disclosed in the final submission.

## Demo path

1. Read the approved facts.
2. Click **Review advertisement**.
3. Inspect each finding and its evidence.
4. Click **Approve corrected draft** or **Send back for changes**.
5. Show the audit history.
