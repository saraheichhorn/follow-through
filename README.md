[README.md](https://github.com/user-attachments/files/32539948/README.md)
# Follow-Through

**Turn meeting notes into owned, dated commitments, and see what's slipping before the next exec sync does.**

👉 **[Try the live demo](https://saraheichhorn.github.io/follow-through/)**

---

## The problem

Leadership meetings produce a steady stream of decisions and commitments. Some of them quietly disappear, not because anyone dropped the ball, but because nobody actually picked it up. "Someone should look into that" is where good ideas go to die.

As a Chief of Staff, closing the gap between *deciding* and *doing* is a core part of the job. Follow-Through is a tool I built to make that gap visible.

## What it does

- **Extracts commitments from meeting notes.** Paste a transcript and it pulls out every decision, action item, owner, and deadline, turning phrases like "end of next week" into real dates.
- **Flags unowned work.** Anything agreed to without a clear owner is highlighted, so it can be assigned before it's forgotten.
- **Tracks follow-through across meetings.** A single view shows what's overdue, what's due soon, and what's on track, with a health bar for the whole portfolio of commitments.
- **Keeps a decision log.** Decisions are recorded with the meeting they came from, so "when did we decide that?" has an answer.
- **Drafts the weekly exec brief.** A short note for leadership covering what slipped, what needs an owner, what's at risk, and what needs a decision.

## Design choices

- **A human stays in the loop.** The tool flags gaps; it doesn't decide who should own something. Assigning accountability takes context and judgment that belong with a person.
- **Review before anything is saved.** In the full version, extracted items are shown for review and editing before they enter the tracker.
- **Built-in data caution.** Users are reminded not to paste confidential or proprietary information unless their company's policies allow it to be used with AI tools.

## About this demo

This public demo runs on a sample leadership meeting from a **fictional company**. All names, people, and data are invented. The sample shows the complete flow, from raw transcript to tracked commitments to the exec brief. The full version uses AI to process any meeting transcript.

## How it was built

Built with [Claude](https://claude.ai) as a single, self-contained web page (HTML, CSS, and JavaScript) and hosted on GitHub Pages.

---

*Built by Sarah Eichhorn.*
