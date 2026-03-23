# First28 — Neonatal Health Support App

**A PM Case Study**

---

## Why I built this

Back in 2018, I was a graduate student of Health Informatics at UC Davis.
My peers and I had identified a real gap: new mothers were being sent home
from the hospital with a newborn and very little structured support for the
most critical window of that baby's life - the first 28 days.

We built a prototype. Without the AI tools available today, we designed a
decision tree by hand, drawing on clinical guidelines and our own research
to map symptoms to risk levels. We published the paper. And then, like most
graduate projects, it stayed on the shelf.

Years later, I came back to it - this time as a practicing PM, and this time
with access to the kind of AI capabilities we could only imagine in 2018.
This project is the answer to a question I've been sitting with for eight
years: what could First 28 actually become?

---

## What this project is

This is a complete end-to-end PM case study: from re-synthesising the
original research in light of what the evidence says in 2024, through
product strategy, UX principles, and AI triage architecture, to a
deployable Python + React Native codebase.

The original decision tree we built in grad school has become a 15-rule
triage engine. The AI pipeline has a hard non-provider boundary enforced
at the architecture level - the LLM is never allowed to diagnose, reassure
falsely, or name a condition. The rules themselves are written to be
human-readable and auditable, because one of the lessons I carried from
the original project is that clinical logic needs to be legible to the
people responsible for it, not buried in a model.

The design is built around one person: a sleep-deprived new mother, alone,
at 2am, holding a baby she's worried about. Every decision - one question
per screen, amber instead of red for "contact your care team," no guilt
notifications for missed days - flows from that constraint.

---

## What I was trying to demonstrate

**Research synthesis into strategy.** The original paper gave me a
foundation. But I didn't stop there - I went looking for what the evidence
says now, eight years on. That updated synthesis changed real product
decisions: day-specific risk thresholds, maternal mental health as a
first-class feature rather than an afterthought, offline-first as a
health equity requirement rather than a nice-to-have.

**Empathy as a design input, not a buzzword.** The users of this app are
not typical tech users. They are exhausted, anxious, and often alone. The
UX section of this case study reflects that in every detail - from the
colour system (warm amber over clinical red) to the streak mechanic that
celebrates consistency without punishing missed days. That kind of thinking
came directly from imagining the person on the other end of every screen.

---

## What this is not

This is a portfolio and educational project that builds on an earlier
academic prototype. The triage rules are based on published clinical
guidelines but have not been formally validated or reviewed by a licensed
clinician. The non-provider boundary in the code exists precisely because
I take that limitation seriously - any real version of this product would
need to go through proper clinical validation and regulatory review before
reaching a real mother and her baby.

The original 2018 paper: [First 28: Design of a Mobile App for Neonatal
Health Risk Assessment and Support for New Mothers](https://iproc.org/2018/2/e11740/) -
Pham, Bluett, Puthran et al., iProceedings 2018.

---

## Get in touch

If you're building something in health tech, or you're looking for a PM
who thinks carefully about what it means to build products that people
depend on - I'd love to talk.

[LinkedIn →](https://www.linkedin.com/in/priyankaputhran/)
[Email →](mailto:priyankanputhran@gmail.com)