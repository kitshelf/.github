# kitshelf

You have a document you don't understand, and a decision to make before you can afford a lawyer, an advocate, or a second opinion.

That's where these kits start. kitshelf is a shelf of free, open-source tools that turn any AI chat into a careful reader: paste the lease, the bill, the estimate, the denial letter, the lab panel, the scam-shaped email — and the kit reads it back to you. Every claim quoted from the document. Every gap marked `[CONFIRM]`. No scores, no verdicts, no invented numbers.

No code to install. No account. No telemetry. You keep every file, forever.

[![100% Markdown](https://img.shields.io/badge/100%25_Markdown-2ea44f)](#what-every-kit-is) [![Privacy](https://img.shields.io/badge/Privacy-local_only,_no_telemetry-8b5cf6)](#what-every-kit-is) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](#license)

## The shelf

Three kinds of kits, one mechanic — *read what they sent you* (decode the documents the world hands you), *read back what your life holds* (organize your own words, without a ghostwriter), *read what you wrote* (audit your own drafts for honesty).

| # | Kit | What it reads back to you | Status |
|---|---|---|---|
| 1 | [**ScamCheck**](https://github.com/kitshelf/scamcheck) | the job offer, rental listing, or "bank" text — before you reply | **v0.1.0 released** |
| 2 | **LeaseLens** | your lease, before you sign | planned |
| 3 | **BillFight** | the hospital bill, before you pay | planned |
| 4 | **DenialAppeal** | the insurance denial, before the deadline | planned |
| 5 | **ClosingDecode** | your closing numbers, before the table | planned |
| 6 | **MechanicLens** | the repair estimate, before you approve | planned |
| 7 | **DepositBack** | the itemized deductions, before you give up | planned |
| 8 | **SubSweep** | your bank statement, before next month | planned |
| 9 | **LabsPlain** | the lab panel, in plain English | planned |
| 10 | **IEPAlly** | your child's IEP, before the meeting | planned |
| 11 | **VisitPrep** | the doctor's visit, prepared | planned |
| 12 | **TomorrowBinder** | the binder your family needs and nobody has | planned |
| 13 | **MemoryBook** | your parents' stories, in their words | planned |
| 14 | **Tribute** | the eulogy, written from real memories | planned |
| 15 | **GrantTruth** | the grant or scholarship application, before you sign your name to it | planned |

## What every kit is

- **100% Markdown.** No install, no server, no API keys. Runs in any AI chat, including fully local models.
- **Local-first, always.** Your documents never need to leave your machine. Kits prompt you to redact before pasting.
- **Fixed labels, never scores.** "Scam markers: 5," with the evidence quoted — never an invented "87% probability."
- **`[CONFIRM]` over invention.** Missing facts are marked for you to verify, never guessed.
- **Tested like software.** Fixture corpora with planted defects and expected detections. A prompt system without fixtures is a guess.
- **A charter with a "what this is not."** Every kit states what it refuses to do, on page one.

## What these kits will never do

Invent a number. Give a verdict you can't check. Upload your documents. Ask for an account. Tell you something is "definitely" anything.

## From the creator of career-kit

The method comes from [career-kit](https://github.com/deghosal-2026/career-kit), the Markdown-only career evaluator that quotes your resume back at you, refuses to invent, and never makes up a score. Same craft, new shelf.

## Status

Kits ship in build order, each with its charter, its fixtures, and a build journal. Shipped: [**ScamCheck v0.1.0**](https://github.com/kitshelf/scamcheck) — the jobs family end to end, its 20-fixture gauntlet recorded on four models, adversarial release gate passed. Next inside it: the rentals, banking, and marketplace families in v0.2.0, romance in v0.3.0. After that, the next kit on the shelf.

## License

MIT, every kit.
