---
workflow: cv-and-cover-letter-tailoring
risk_tier: minimal, personal non-professional use of a general-purpose AI to draft your own job applications, with human review of every output
owner: Laurien (sole owner and user)
last_audit: 2026-10-30
---

# CV and cover letter tailoring with Claude

## Risk classification
Minimal risk, and largely outside the Act's scope. Article 2(10) excludes natural persons using AI for purely personal, non-professional activity, and applying for your own jobs fits that. The employment use case in Annex III (high-risk) covers AI used by employers to recruit, screen, or evaluate candidates; the AI screeners reading your applications carry that burden, not you. No fundamental rights impact assessment is needed. Workflow is currently dormant.

## Five-point hygiene check
bias:         PASS  - output only describes you; you review every draft, and no decision about another person is made.
privacy:      FAIL  - former colleagues' words and former employers' project details are sent to a third-party AI service without their knowledge.
consent:      PASS  - you are the only person the output is about; quoted feedback was given to you and is used in the conventional CV sense, not to profile anyone.
attribution:  PASS  - quotes come from real feedback and you check them before sending; no invented endorsements reported.
transparency: PASS  - the Act imposes no disclosure duty on an individual for a privately written application; see remediation 2 for employer-policy risk.

## Remediation (do these in order)
1. Before reusing this workflow, strip names of quoted colleagues, client names, and any non-public project figures from prompts (use "senior manager" or rounded figures), and confirm your Claude privacy setting on whether chats are used for model training.
2. Check each employer's application terms for rules on AI-assisted applications, and disclose AI help where asked; some employers now treat undisclosed AI drafting as a breach of honesty in the process.
3. Keep a verified master CV as the only source the AI tailors from, so no inflated or invented claims creep in; re-audit if the workflow restarts.

## Note
This is general education on the EU AI Act, not legal advice.
