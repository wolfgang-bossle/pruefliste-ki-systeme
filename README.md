# Review questions for AI systems

**Selection · Build · Operation · Evidence** — a two-language questionnaire (German and
English in one document) for the sign-off of an AI system: the questions asked by internal
audit, by the sponsor, by data protection.

**Licence:** [CC BY-ND 4.0](LICENSE) — pass it on freely, including commercially,
provided you pass it on unchanged. [Details below](#licence).

## What you do with it

You take it into a review of a finished system and work through it question by question.
What you learn at the end is not whether the system is good. It is something more useful:
where nobody can produce anything.

Every question names, in a second column, what does **not** count as an answer — the
assurance, the intention, the policy nobody has read. Most of the questions are blocking:
where the answer is missing, the system is not ready to go into operation.

That is the part of AI governance a review can actually test: not the policy, but the
evidence behind it.

**→ [Read the questionnaire](questionnaire.md)** — both languages, the full set of
questions with their sources.
**→ [Download the current edition](../../releases/latest)** — the same questions as a PDF
made for print, together with the derivation, attached to the release.

## Where the questions come from

They are derived from the exam guides of the four Claude certifications. Those guides are
public and describe what a person should be able to do. A capability cannot be handed to a
reviewer, so every published objective was held against one single question:

> Does this produce evidence — a document, a log, a test run, a decision with a person and
> a date?

Most objectives did not survive that question, and the reasons are recorded rather than
summarised: an objective that another one already answers with the same document, one that
can be met with an assurance, one that describes a human skill instead of a property of the
system, one that is pure product knowledge. What remains carries its origin with it.

The questions contain no wording from Anthropic's materials, and no exam content. There is
no connection to Anthropic, and none is claimed.

## What is in the download

One PDF, German first and English second, containing:

- **the questionnaire** — a few pages, made to be carried into a meeting;
- **the derivation behind it** — for every question the exam objective it came from, with a
  pointer to the place in Anthropic's public documentation where one exists, and every
  deletion with its reason.

So what is documented is not only what is asked, but why the rest is not asked.

## Who is behind it

Wolfgang Bossle, Registered CPA, Claude Certified Architect.

The perspective is that of accounting and audit — the side of the table that has to be
satisfied. The questions themselves are vendor-neutral and tied to no one field.

For context: my own system is still being built. I write from the design side, not from
live operation.

## How to respond

Corrections, gaps and objections are welcome. The way that works is a **direct message on
LinkedIn**: <https://www.linkedin.com/in/wolfgang-bossle/>

Issues in this repository are read, but answered more slowly. Every change that came from
outside is recorded in [CHANGELOG.md](CHANGELOG.md) — with the hint it followed.

## What this is, and what it is not

The questionnaire is offered as **non-binding assistance**. It is not an audit, not a
review, not legal or tax advice. No assurance is given as to completeness or correctness,
and no judgement is passed on any system, vendor or legal position. Whoever uses it decides
which questions apply in the case at hand and whether an answer is sufficient.

This statement applies to every edition. From edition 2 onwards it is also printed on the
first page of the document itself; edition 1 does not carry it, so for that edition this
page is where it stands.

## Planned next steps

None of this is a promise. It is where the work currently points.

**Edition 2** follows a first round of review. Every objection raised is worked through one
by one, against a single test: does the questionnaire get better, yes or no. What that lets
in, and what it leaves out, will be visible in [CHANGELOG.md](CHANGELOG.md).

**A second anchor, beside the exam guides — an idea, not a decision.** The questions are
derived from one vendor's certification guides. That is a narrow footing for a document
meant for a review. The obvious counterweight is the body of rules a German reviewer
already works with: the EU AI Act, the GDPR, the GoBD, the Commission's guidance on the
Article 50 transparency obligations, the German Trade Secrets Act, the US CLOUD Act, and
the IDW pronouncements — IDW PS 861 on the audit of AI systems, IDW AdvH 6.003 on the
use of generative AI.

Nothing in the questionnaire would change because of this. The place for it would be the
rationale, where each question already names where it comes from — a second line beside
the first, so a question can be traced not only to a capability someone should have, but
to a rule someone has to keep. Whether that is worth its weight is the open question.

## Licence

The questionnaire, its text and its data are licensed under
**[Creative Commons Attribution-NoDerivatives 4.0 International](LICENSE)** (CC BY-ND 4.0).

You may share it, including commercially and including with clients, **provided you pass it
on unchanged**. You may produce an adapted version for your own use; you may not share that
adapted version publicly.

**When you share it, these must remain with it** (Sec. 3 a.1 of the licence):

- the name of the author
- the copyright notice
- a reference to this licence
- **a reference to the disclaimer of warranties**
- a link to the original

Ready to copy:

> „Review questions for AI systems" by Wolfgang Bossle, licensed under CC BY-ND 4.0 —
> https://github.com/wolfgang-bossle/ai-system-checklist — no warranty is given (see Sec. 5
> of the licence and the reservation printed in the document).

Nothing in the licence permits any claim of a connection to, or endorsement by, the author
(Sec. 2 a.6). Name and title are not licensed as marks (Sec. 2 b.2).

**If you need more than the licence allows** — a translation, or an adapted edition you
want to pass on — ask. Permission is given case by case, in writing, for the edition and
the purpose named in it. Such an arrangement is separate from and independent of this
licence (Sec. 7 b). The way to ask is the direct message above.
