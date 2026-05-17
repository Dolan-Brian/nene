# Nene

**A concept prototype for guided life planning.**

Nene is an interactive prototype that explores how a conversational, guided experience could help people organize their accounts, contacts, and instructions so the people you love don't have to piece it together after you're gone.

[Try the live prototype →](https://cerulean-belekoy-a45eaf.netlify.app/)

---

## Why I Built This

I lost two close family members in less than two years. Both times, I was the person who had to sort through the aftermath: tracking down accounts nobody knew existed, spending hours on hold with banks that couldn't help without the right paperwork, and dipping into my own savings to keep their bills from going into default.

I wasn't mourning. I was managing. And the worst part was realizing that most of the pain could have been avoided if someone had simply organized things ahead of time.

So I started designing what that tool could look like. Not a vault. Not a legal service. Not another app that makes you feel like you're filing taxes. Something calm, conversational, and personal. Something that meets people where they are instead of overwhelming them with 200 empty fields.

Nene is the result of that exploration.

---

## What It Does

Nene walks users through organizing their life one step at a time:

**Email accounts** — what exists, what it's used for, whether it's still active. No passwords, just context.

**Financial accounts** — banks, credit cards, retirement accounts. The information someone would need to know exists, not the credentials to access them.

**Key contacts** — attorneys, doctors, financial advisors, insurance agents. The people someone would need to call.

**Trusted contacts** — who should have this information. A spouse, a sibling, a close friend.

**Printable plan** — everything compiled into a prioritized, printable summary organized by urgency (first 48 hours, first week, first month, when ready). Store it in a safe, give it to your attorney, or keep it in a filing cabinet.

---

## What I Was Exploring

This prototype was a way to test a few product hypotheses:

**Can conversational UX reduce abandonment?** Every competitor in this space uses a dashboard with dozens of empty fields. Most people open it, feel overwhelmed, and close the tab. Nene asks one question at a time.

**Can emotional positioning change engagement?** "Because the people you love shouldn't have to guess" is a fundamentally different frame than "Your Digital Vault. For Life." I wanted to see if warmth and care could make people lean in instead of avoid.

**Can a printable output be the right MVP?** Instead of building complex authentication, encryption, and multi-user access systems, what if the first version just helps you organize and print? That removes massive technical complexity while still solving the core problem.

---

## What I Learned

Building Nene taught me much about consumer behavior and product thinking than it did about code. Generally speaking,the hardest problems weren't technical. They were questions like: how do you talk about death without making people close the tab? How much information is enough to be useful without being overwhelming? When do you push someone to keep going versus letting them come back later?

The answers to those questions live in the copy, the flow, and the pacing of the prototype more than in the code itself.

This project also changed how I think about AI as a tool. I used AI not just to write code, but as a genuine thought partner for product strategy: pressure-testing positioning, playing devil's advocate on business model assumptions, researching competitors, and stress-testing the "why now" argument against a market where multiple funded startups have failed. The back-and-forth sharpened my thinking in ways that working alone wouldn't have.

---

## Design Details

**Palette:** Slate (#3D3555) + Lavender (#B8A9D4) — chosen to feel calm and trustworthy without being clinical. Initially I toyed with the idea of brighter, even neon colors but it didn't seem appropriate for the subject matter.

**Typography:** Inter Tight (headings) + Palanquin (body) — modern headings with soft, readable body text.

**Built as:** A single-file React application. No build step, no dependencies, no server. One HTML file that runs in any browser.

---

*This is a concept prototype, not a live service. Nene does not store data between sessions.*

*Built by Brian*
