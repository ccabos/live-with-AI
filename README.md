# live-with-AI

Essays on living with AI that is more intelligent than us — in the sense that matters now:
not a speculative superintelligence, but machines that match or beat the typical person across
most of the cognitive work our economies and institutions run on.

The through-line is one distinction: **capability** (what can be done), **value** (what the
market will pay for), and **worth** (what makes a life matter) rode together for all of human
history, and cheap machine cognition is pulling them apart. Everything else — how authority and
trust shift, how the economy is repriced, which work remains, whether thinking is still worth
the effort, who is allowed to hold the machines — follows from that seam opening.

## Read it

The site renders everything as web pages: **https://ccabos.github.io/live-with-AI/**

| Piece | Source | What it is |
|---|---|---|
| Living With AI That Is More Intelligent Than Us | [`essay-draft.md`](essay-draft.md) | The full essay, sections I–XI (~10,000 words) |
| The Machines Will Be Smarter. The Question Is Whether We'll Be Wise. | [`op-ed.md`](op-ed.md) | The same argument at op-ed length |
| More Code, Not Fewer Coders | [`software-developers.md`](software-developers.md) | Spin-off J: why cheap AI code multiplies developers rather than replacing them (Jevons's paradox) — and what the expansion costs the people it rewards |
| The Attention Bottleneck | [`attention-bottleneck.html`](attention-bottleneck.html) | Infographic for spin-off K: capability got cheap, attention didn't |
| The essay, in one map | [`essay-map.html`](essay-map.html) | Infographic of the whole essay's argument |

Everything exists in both languages: essays as `*.de.md`, infographics as `*.de.html`
(*Der Aufmerksamkeitsengpass*, *Fähigkeit. Wert. Würde.*), each linked from its counterpart.

## Working material

[`essay-outline.md`](essay-outline.md) / [`essay-outline.de.md`](essay-outline.de.md) are the
scaffolding, not a finished piece: the section-by-section argument, a credibility checklist,
and a lettered catalogue of possible follow-up articles (A–K) with their argument spines as
Mermaid flowcharts. Spin-offs J and K are written; the rest are candidates.

## How the site is built

GitHub Pages with Jekyll. The Markdown files are the single source of truth;
[`_layouts/default.html`](_layouts/default.html) renders them as reading pages and renders the
outline's Mermaid diagrams client-side. The two infographics are standalone, self-contained
HTML — no build step, no external assets beyond the Mermaid library on outline pages.
