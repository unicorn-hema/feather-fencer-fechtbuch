# Chapter framework

**Working agreement · version 0.3 · 2 October 2026**

This is the reference for writing chapters of *Feather Fencer Fechtbuch*.
It records the agreed structure and method. It is a starting point, not a canon:
sections may be shortened, expanded, or omitted when the material warrants it.
The published *Zufechten* chapter provided the first practical editorial test of the
framework and template. Keep testing the design against later chapters rather than
making its chapter-specific decisions universal.

See the [visual specimen](../wip/chapter-layout.md) and the
[copyable Markdown template](https://github.com/unicorn-hema/feather-fencer-fechtbuch/blob/main/templates/chapter.md).

## Purpose and organising principle

The project is an author's modern fechtbuch: a reading of Liechtenauer's teaching
that makes the path from historical text to personal interpretation and modern
HEMA application visible. Chapters follow the Zettel and its glosses, rather than
an independently imposed modern training syllabus. Final articles are in English;
clearly marked working notes may be in Czech.

## Editorial independence and evidence

Historical glosses are primary evidence for this project, not authorities with
which the author must always agree. The fechtbuch may advance a different
historical reading or a deliberately different modern application. Such a
departure must be visible and argued, not silently attributed to the source.

- **Source:** report what each witness actually says, including consequential
  differences and limitations. Reproduce a gloss faithfully even when the
  author's conclusion differs from it.
- **Historical interpretation:** explain the author's reading and its basis.
  Where it conflicts with a gloss or another plausible reading, identify the
  exact disagreement, relevant supporting evidence, counterevidence, and
  uncertainty. Practical success alone cannot establish historical intent.
- **Hypothesis:** label plausible but insufficiently supported explanations
  explicitly, for example as an author's hypothesis. State the reasoning and
  the status of any modern observations used to motivate it.
- **Modern application:** the author may reject or adapt a historically attested
  procedure to meet present-day HEMA conditions. Identify what is being
  transferred, what is being changed, and why; do not project modern usefulness
  back onto the historical source.

Actively look for evidence that challenges a preferred reading, rather than
using sources only to confirm it. Disagreement need not be resolved by forced
consensus: revise an unsupported historical claim or mark its status honestly;
a modern model can remain useful while differing from the glosses. In personal
authorial sections use the first-person singular (“I”), not a fictitious
collective “we”. Source summaries should remain neutrally attributed.

## Source groups

- **GNM Hs. 3227a:** considered separately as one principal body of commentary.
  Use the manuscript identifier rather than treating “Döbringer” as certain
  authorship of the entire gloss.
- **RDL:** Ringeck, pseudo-Peter von Danzig, and Lew considered together as a
  comparative group, while preserving the identity of individual textual witnesses.
  A shared summary is an editorial synthesis, not a quotation from a single source.
  Prefer one concise account of genuinely shared teaching, followed by attributed
  differences and continuations. Expand the individual witness accounts only when
  real differences warrant it; do not repeat their common instructions three times.
- **Additional sources:** Medel and other relevant texts may be introduced where
  useful. State why they matter; they may challenge as well as support our reading.

The working premise is that comparison between 3227a and RDL will often concern
approach and emphasis, while comparison within RDL will often concern details.
This is a hypothesis to test passage by passage, not a conclusion imposed on them.
Different exposition does not by itself establish a different fencing system.
Silence is not disagreement, and related texts are not automatically independent
confirmations. Present both principal groups before attempting a synthesis.

## Default chapter sequence

### TL;DR

Open with a short authorial overview, normally one or two paragraphs: what the
author takes the passage to teach and what carries over (or changes) in modern
HEMA. It is a reading aid, not another source summary. Keep uncertainty honest
and avoid promising a result that the chapter does not argue.

### 1. Zettel

Present the original wording, an attributed verse translation (or a clearly
labelled link to one that is not reproduced), and a sense translation. Identify
the textual witness or edition, passage, and translator for each. Do not copy a
third-party rendering without permission or an applicable licence. Translate
the sense from the original, not from the verse adaptation. If wording follows
a gloss's fuller explanation, explicitly label it *gloss-informed*; do not pass
it off as an unambiguous literal translation of the Zettel. Rhyme and metre
must not decide interpretation. Preserve consequential ambiguity or explain the
choice. A verse rendering may be deferred rather than forced.

### 2. Historical glosses

Give separate treatment to 3227a and RDL, linked to actual passages and publicly
available translations (for example on Wiktenauer). Identify the translator
and witness, not just the website. Summarise the *relevant teaching*, rather
than paraphrasing every line. Distinguish summary from quotation. Within RDL,
start with the common ground and then attribute meaningful differences,
additions, omissions or alternative continuations. Do not silently blend them.
A brief 3227a/RDL comparison is useful when it adds something not already said.

### 2a. Language and translation commentary — optional

Keep commentary accessible from the passage it concerns. For a short material
qualification, explain it inline; for substantial commentary, place a linked
endnote marker beside the passage and the full note at the end of the chapter.
Show the original wording, existing rendering, proposed reading, and argument.
A note may explain ambiguity without alleging a translation error.
Inspect vocabulary, grammatical relationships, and context. If the issue depends
on a transcription, abbreviation, or editorial punctuation, consult the manuscript
image where available and record any remaining limitation. Separate a linguistic
finding from the technical interpretation drawn from it.

### 3. My historical interpretation

Explain what the author believes the text describes in its historical context,
why, and with what uncertainty. Keep source statements, inference, and hypothesis
recognisable. Success in modern sparring does not by itself establish historical
correctness. Preserve the author's own empirical claim accurately, rather than
silently weakening or upgrading it; distinguish the observation from any
inference about historical prevalence. Put a material uncertainty beside the
claim it limits.

### 4. My application in modern HEMA

Explain how the author applies the reading today, under which conditions, and
for what purpose. Mention relevant rules, equipment, training constraints, or
deliberate adaptations. Historical reconstruction and modern usefulness are
different claims. Practical examples, exercises, or observations belong here
when they help, but are not mandatory subsections.

Agreement with the historical prescriptions is not required in this modern
section. For a deliberate departure, explain the historical baseline, the
present-day problem, the alternative adopted, its justification, and its limits.
Apply the evidential discipline set out above.

### 5. Notes and open questions

Use for reader-relevant supplementary sources, alternatives and genuinely open
questions; omit the section when empty. Do not publish the internal editorial
audit, revision checklist, working history or private voice notes as if they
were chapter content. Do not move an essential qualification here merely to
make the main argument look more certain. References must remain reachable from
the claims they support, whether inline or via linked endnotes.

## Images and presentation

Place images directly beside the relevant discussion. Give each a useful caption,
alternative text, source/credit where applicable, and a clear role: historical
image, reconstruction, or modern application. Decorative placeholders belong only
in the layout specimen. Do not imply that a modern diagram is historical evidence.

Keep the original Zettel, verse translation or attributed link, and sense
translation accessible without switching tabs. For the reader's flow, prefer
short linked footnote markers for lengthy bibliographies and translation notes,
with end-of-page definitions and automatic backlinks; do not hide consequential
qualification or source attribution. MkDocs has the `footnotes` extension enabled:
keep footnote definitions after the closing chapter layout `<div>`, and remove
unused markers. Typography and explicit labels distinguish source, translation,
and authorial argument; colour is supplementary. Comparison panels stack on
small screens.

## Chapter collaboration workflow

Use one dedicated conversation per chapter so that its discussion, questions,
and revisions remain together. The first published substantive chapter is
**Zufechten — Zettel 9–16**. Treat its editorial choices as a tested example,
not binding answers for later passages.

### Starting or resuming a chapter

Read the current version of this framework from GitHub. If a chapter draft or
progress note already exists, read it as well before continuing. Do not assume
that another conversation's context is available. If a needed discussion or
source is missing, ask for that specific material rather than reconstructing it
from memory.

Begin with the chapter topic, the intended scope, and the relevant Zettel and
gloss passages. A link to this framework and the chapter's existing files should
be enough to locate the recorded working context.

### From discussion to text

1. **Initial voice discussion.** Explore the author's understanding, practical
   experience, intended argument, and desired coverage. Begin with discussion,
   not a finished chapter draft. Working discussion may be in Czech.
2. **Source comparison and issue list.** Compare the proposed content with the
   relevant 3227a and RDL passages and inspect the original wording where it
   matters. Identify ambiguities, contradictions, gaps, and questions. Keep the
   author's position separate from suggestions introduced by the assistant.
3. **Voice refinement.** Work through those issues with the author. Record what
   was settled, what remains provisional, and what still needs checking.
   Unresolved questions may remain open; do not manufacture agreement.
4. **First English draft.** Once the discussion has established a usable basis,
   the assistant proposes a chapter using the agreed template. Preserve the
   author's intended argument and mark unresolved points where they matter.
5. **Content and evidence review.** Check claims and attributions against the
   witnesses, resolve or disclose translation uncertainty, and distinguish source,
   historical interpretation, hypothesis, modern model and empirical observation.
6. **Separate English/readability review.** Correct grammar, terminology,
   presentation and consistency of the first-person authorial voice without
   silently changing the author's meaning or degree of confidence.
7. **Author approval and publication preparation.** Show the actual proposed
   reader-facing text; remove internal editorial notes, retain useful public
   uncertainties, and adapt it to the chapter layout and navigation.
8. **PR, checks and publication.** Submit an approved candidate on a branch via
   pull request, run `mkdocs build --strict`, review layout when possible, and
   merge to `main` only after explicit authorisation. PR checks alone do not
   provide a public GitHub Pages preview; if appearance matters before merging,
   prepare a separate rendered preview.

Base written records on the discussion or transcript actually available.
Clarify uncertain transcriptions of technical terms or quotations when they
affect the argument.

### Keeping the working context portable

GitHub holds the current framework, chapter text, and a concise record of decisions
needed to resume work. Conversations hold the exploratory discussion.

At a useful stopping point, maintain a short chapter progress note, for example
`notes/chapters/zufechten.md`, containing:

- chapter scope and links to the current draft;
- exact source passages, editions, translations, and links used;
- agreed interpretations and the reasons for consequential choices;
- unresolved questions and alternatives, clearly marked as such;
- the current stage and the next useful step.

Record decisions rather than copying an entire voice transcript. Only material
intended for public access belongs in this public repository. Internal editorial
notes can remain outside the public repository; do not automatically copy them
into the reader-facing chapter. When starting a
new conversation or returning after a break, consult that note alongside the
framework and draft. A link is a reference to read, not an automatic transfer of
conversation history.

## Using and revising this framework

Copy `templates/chapter.md` to the appropriate location under `docs/`, fill only
the relevant sections, and add the page to navigation. Remove editorial prompts and internal audit material
before publishing a finished chapter. Choose and record the exact Zettel witness,
transcriptions, and translations before writing substantive claims.

Record substantive methodological changes here in Git history. The specimen
demonstrates presentation only and contains no historical assertions or quotations.
