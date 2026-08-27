# CodeAlpha_PhishingAwarenessTraining

A phishing awareness training module built as Task 2 for the CodeAlpha Cybersecurity Internship — a slide deck covering how phishing attacks work, how to recognize them, and an interactive quiz to test what you've learned.

## Contents

| File | Description |
|---|---|
| `Phishing_Awareness_Training.pptx` | 12-slide presentation covering the full module |
| `quiz.html` | Self-contained interactive quiz — no install, no server, just open in a browser |

## What the presentation covers

- **What is phishing?** — the basics, and why it targets people rather than software
- **Anatomy of a phishing attack** — the 5-step playbook attackers follow (research → craft the lure → deliver & hook → harvest → exploit access)
- **Types of phishing** — email phishing, spear phishing, whaling, smishing, vishing, clone phishing, pharming, and QR-code phishing ("quishing")
- **Social engineering tactics** — the psychological levers behind the click: urgency & fear, authority, trust & familiarity, curiosity, scarcity & reward
- **Red flags in emails** — mismatched senders, urgent tone, generic greetings, suspicious links, unexpected attachments, credential/payment requests
- **Red flags in fake websites** — look-alike domains, the HTTPS padlock misconception, off-brand design, suspicious login forms
- **Real-world case studies** — the $100M+ Google/Facebook Business Email Compromise scam, a $243K AI-voice vishing attack on a UK energy firm, and the Twilio smishing breaches
- **Best practices** — pausing before acting, verifying through a second channel, checking real sender/URL, password managers, MFA, keeping software updated
- **Incident response** — what to do immediately if you've clicked something you shouldn't have
- **Key takeaways** summary slide

## Interactive quiz

`quiz.html` is a 10-question multiple-choice quiz covering the material in the deck — spotting phishing red flags, identifying social engineering tactics, and recalling the real-world case studies. It tracks your score, shows an explanation after every answer, and gives a results screen with a "Try Again" option.

### Running it

**Option 1 — locally:** download `quiz.html` and open it in any browser. No dependencies, no internet connection required.



## Sources for real-world statistics and case studies

- Google/Facebook Business Email Compromise scam — NPR, NBC News, U.S. Department of Justice reporting on *United States v. Evaldas Rimasauskas*
- UK energy firm AI-voice vishing incident (2019) and Twilio smishing incidents (2022, 2024)
- Phishing volume and detection statistics — Statista, industry phishing reports (2024–2025)

## Disclaimer

This module is for security awareness and education only. All examples are drawn from public reporting on real incidents; no proprietary or confidential information is included.

## License

MIT
