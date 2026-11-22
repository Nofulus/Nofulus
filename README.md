# Hi, I'm Randeep Pal

I'm a Grade 11 IB student in Oakville, Ontario. I make YouTube videos on my channel [Nofulus](https://www.youtube.com/@Nofulus), go to hackathons, and like startup and entrepreneurship culture. Here are a couple of projects I worked on.

## Projects

### [Donna](https://github.com/yinbri/donna): an AI recruiting coordinator you can check in 12 seconds
*YC Startups × ElevenLabs Hackathon, University of Waterloo, Nov 2026 · Team 10*

A candidate applies and Donna runs a short voice screen (ElevenLabs). Every score comes with a ▶ button that plays the exact seconds of the call it's based on. Donna then proposes an interview, but she can't book it on her own.

**My part: the trust and ops lane**
- **Approval gate.** Donna never holds the founder's calendar access. [Alter](https://alterauth.com) holds the Google grant and keeps every calendar write pending until the founder approves. Tested live: a write without approval was held, approval released it, and Google sent the invite.
- **Tracing.** [TraceRoot](https://traceroot.ai) spans for each pipeline and approval step, grouped by candidate, with IDs only and no candidate data.
- **Real roles.** Seeded the sponsor startups' open roles from their YC job pages.
- **Live pilot.** Runbook, consent copy, a QR table sign and rules for counting only real screens.

`TypeScript` · `Wasp` · `Prisma` · `ElevenLabs` · `Alter` · `TraceRoot`

### [Meraklis](https://github.com/Aaru1801/Meraklis): local-first civic AI for Toronto renters
*The Spark Hack Series, Toronto (NVIDIA · ASUS · Antler), May 2026 · Team "Edge Cases"*

Eight cooperating agents investigate any Toronto apartment building using the City's RentSafeTO inspection records. They score its risk, ground tenant rights in Ontario law and draft a 311 complaint. Everything runs on an NVIDIA DGX Spark, with no cloud AI.

**My part: UI/UX design, demo and pitch**
- Designed the dark "operator console": the Toronto map and 3D building views, and the investigation workspace with its live agent trace.
- Shaped the problem framing, research, demo and pitch.

`React` · `TypeScript` · `Python` · `NVIDIA DGX Spark`

## Get in touch

[LinkedIn](https://www.linkedin.com/in/randeep-pal)
