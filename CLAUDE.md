# CLAUDE.md — theforgetting.org

> **Reconciled model, installed 16 Sep 2026.** The estate has one written
> model — `~/Documents/Work/publishing/05-reconciled-model.md` — and this
> file is derived from it. This repo had no local clone until 16 Sep 2026
> and no CLAUDE.md at all; the March 2026 brief (`Work/publishing/04-theforgetting.md`)
> described a pen-name site that was never built.

## What this site is

Long-form essays on **music as embodied, contextual experience**, with AI
and technology as the recurring character that shows what goes missing
when you strip the body and the context away. Its own aesthetic and its
own voice: **it borrows nothing from the other three sites and lends
nothing to them.**

**Under Stephen's own name.** The Nikola Newton pen name in the March
brief was never applied — all seven live articles are bylined "Stephen",
`params.author = "Stephen"`, and the strapline discloses the method
openly. **Retired 2 Sep 2026.** Do not introduce a pen name, do not
re-byline, do not "soften" the connection to Stephen's other sites.

The method statement stands and is a feature, not a caveat: *"A series
of essays developed through human-AI collaboration. Ideas and frameworks
are mine; articulation gets help."* `/about/` explains it (architect and
contractor). Keep both.

## Where things live

- **Repo: github.com/Gorse-Sounds/theforgetting** (public — the only
  public repo in the org). Local clone `~/WebstormProjects/theforgetting`,
  made 16 Sep 2026; it keeps the repo's name rather than the `sites-*`
  convention so the folder and the remote never disagree.
- Hugo + **PaperMod** (git submodule at `themes/PaperMod`; run
  `git submodule update --init` after cloning). GitHub Pages via
  `.github/workflows/hugo.yml`; `static/CNAME` = `theforgetting.org`.
- Substack-shaped by design: permalinks `/p/:slug/`, serif reading
  register in `assets/css/extended/custom.css`, Giscus comments via
  GitHub Discussions.
- Content: `content/posts/` — seven articles, Nov 2025 onward, **Series 1:
  Embodied Listening** (bass in the chest; the beat before you know it;
  listening together; the chord that makes you cry; the deceptive
  cadence; furniture that sings; music remembers what you've forgotten).
  `README.md` is the original article plan and still lists the ideas
  not yet written.

## The estate (four sites, one model)

- **theforgetting.org** — this site: the essays.
- **stephendwolff.com** — the person and the work: projects, the RiTA
  paper, notes, experiments, `/music/`, **and the six-piece series with
  its PhraseEngine experiments (decided 14 Sep 2026 — it does not come
  here).**
- **gorsesounds.co.uk** — commercial audio software.
- **maxgatedigital.com** — the consultancy.

Substack is a beacon, not a presence: it links to everything Stephen publishes,
this site included, and nothing is written for it (21 Sep 2026). Nothing here is a
service, a product or a case study, and the sister sites never cite
this one as such. **Text-only, by decision (Stephen, 21 Sep 2026)** — no audio;
the one open thought is accessibility features for blind readers, undecided.

## What publishes here

- Series 1 is complete. **Series 2 — *The Forgetting***, a
  signal-processing critique series, is the planned next run; its
  ideas are in `README.md`.
- Anything that is an essay on musical experience in this voice. Not
  research notes, not project logs, not the recital-programme series.
- Levitin (*Music as Medicine*, 2024) is the recurring reference; the
  articles came from working through it — say so where relevant, as the
  strapline already does.

## Voice

**British English** — and this is the one live defect: `hugo.toml` has
`languageCode = 'en-us'` and the copy follows ("Math", "cataloging",
"synchronization"; the deceptive-cadence title says "Math" where the
March brief said "Maths"). The estate rule is `en-GB` everywhere. Fix the
config and sweep the seven articles' spellings; nothing else in them
changes. Otherwise: first person, plain, unhurried, one idea per essay;
the reader is a listener, not a student.

## Fixed facts

- Byline: Stephen. Author param: Stephen. No pen name.
- Domain: theforgetting.org. Comments: Giscus / GitHub Discussions.
- Never invent studies, figures or citations — `TODO(stephen)` markers.

## Definition of done — housekeeping (nothing here is owed to anyone)

- [ ] `languageCode = 'en-GB'`; American spellings in the seven articles
      corrected; `og:locale` checked after build
- [ ] Submodule initialised in this clone; `hugo` builds clean locally
- [ ] Series 2 outlined from `README.md` when Stephen wants it — not
      before the recital programme's outputs

## Session conventions

Small commits, imperative mood. Never alter the method statement or the
byline. If a trade-off arises between this site and the series on
stephendwolff.com, the series wins — it is on the 1 Jan list; this
isn't.
