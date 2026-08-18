# Lovable prompt — codeforindia.org/hackathon

Paste the block below into Lovable to build/replace the `/hackathon` page.

---

Build a **Hackathon landing page** at the route `/hackathon` for **Code for a Billion**, a hackathon by Code for India. Match the existing site's fonts, colors, and spacing. Make everything fully responsive (cards stack on mobile) and accessible (real `<a>` links, aria-labels, strong contrast). All external links open in a new tab (`target="_blank" rel="noopener"`). Build these sections top to bottom:

**1. Hero**
- Eyebrow: "OFFICIAL IDE · CODE FOR A BILLION"
- Headline: "Build for a billion lives."
- Subhead: "Code for a Billion is a hackathon to build technology that can impact a billion citizens. Solve a problem that affects millions, deploy it, and prove real impact. The official IDE is **AgentFoundry (AF)**."
- Two buttons: primary "Start building in AgentFoundry" → https://agentfoundry.me ; secondary (outline) "Submit your project" → https://github.com/karlmehta/code-for-a-billion/issues/new?template=submission.yml
- Small line under buttons: "🏆 $17,500 in prizes · Awarded at a December ceremony in New Delhi"

**2. Prizes**
- Heading "Prizes". Three cards: "🥇 First — $10,000", "🥈 Second — $5,000", "🥉 Third — $2,500".
- Caption below: "Total prize pool $17,500. Winners are honored at a **December ceremony in New Delhi**, before dignitaries from government, venture capital, and industry."

**3. How to participate** (4 numbered step cards)
1. "Build in AgentFoundry" — Start your project in AF, the official IDE. Ideate, code, and iterate with agents.
2. "Publish your repo" — Push to a public GitHub repository with a README explaining how to run it.
3. "Record a demo" — A 2–3 minute video or a live link showing the real thing working.
4. "Submit on GitHub" — One click; a structured form captures your problem statement, repo, and demo.

**4. How you'll be judged** — heading + subline "Four criteria, weighted equally — 25% each." Four cards, each with a "25%" badge:
- "Size of the problem" — How many citizens face it; the larger the number affected, the higher the score.
- "Severity of the problem" — The level of human suffering, or the economic loss, the problem causes.
- "Quality of the solution" — How well it's designed and how effective it is at actually solving the problem.
- "Proven impact" — Actual deployment data; real evidence of impact in the field.
- Under the cards, a link "See the full judging rubric →" → https://github.com/karlmehta/code-for-a-billion/blob/main/JUDGING.md

**5. Submit call-to-action band** (accent background)
- Heading "Ready to build?" + line "Build in AgentFoundry, publish your repo, record a demo, and submit — everything happens in one place."
- Buttons: "Open AgentFoundry" → https://agentfoundry.me ; "Submit your project" → https://github.com/karlmehta/code-for-a-billion/issues/new?template=submission.yml
- A row of text links: 
  - "Submission hub" → https://github.com/karlmehta/code-for-a-billion
  - "Judging rubric" → https://github.com/karlmehta/code-for-a-billion/blob/main/JUDGING.md
  - "Browse submissions" → https://github.com/karlmehta/code-for-a-billion/issues?q=is%3Aissue+label%3Asubmission
  - "Q&A / Discussions" → https://github.com/karlmehta/code-for-a-billion/discussions

**6. Footer line:** "Organized by Code for India. Official IDE: AgentFoundry."

Also add a "Submit project" button in the top navigation that smooth-scrolls to the submit band. Leave a clearly-marked placeholder for **Dates & Deadline** ("TBD") near the hero so we can fill it later.
