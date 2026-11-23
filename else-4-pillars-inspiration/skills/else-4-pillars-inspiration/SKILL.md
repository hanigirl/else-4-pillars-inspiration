---
name: else-4-pillars-inspiration
description: Four-pillar inspiration + competitor research that lands as a FigJam board with real embedded screenshots (not just links). Pulls from (1) direct competitors, (2) million-user consumer apps for conventions the audience already knows, (3) the broader ecosystem + aspirational adjacent domains, and (4) visual design trends (Dribbble / Behance / Awwwards). Use this WHENEVER the user wants inspiration, references, a benchmark board, a mood board, competitor research, trend research, or to explore design directions for a screen or flow — including "מחקר השראות", "השראות", "תביא רפרנסים", "בוא נחקור מתחרים", "מה עושים אחרים", "benchmark", "find references", "explore directions" — even if they only name a single source like Mobbin or Dribbble. Always open by asking what the project/topic, audience, and specific screen/pattern are before searching.
metadata:
  tags: inspiration, benchmarking, competitor-research, mobbin, dribbble, figjam, trends, references
---

# Inspiration Research — The Four Pillars

This skill runs a **structured inspiration sweep** and lands it as a **FigJam board with real embedded screenshots**. It exists because "find me some inspiration" usually collapses into a thin list of direct competitors or a pile of Mobbin links. Real inspiration research triangulates from four different angles, each answering a different question — and the designer gets far more out of it when the references are *on the board as images they can see*, grouped and annotated, not as URLs.

You are the researcher. Your job is to be deliberately broad: a bank app should not only look at other banks. The value is in the angles the user didn't think to ask for.

## The four pillars

Each pillar answers a distinct question and has its own primary sources and selection lens. Build **one FigJam section per pillar**.

| # | Pillar | The question it answers | Primary sources |
|---|--------|------------------------|-----------------|
| 1 | **Direct competitors** | "How do products solving *my exact problem for my exact audience* do this?" | Mobbin (`search_screens`/`search_flows`), then web search to name the real direct competitors |
| 2 | **Million-user apps** | "What conventions does my audience *already know* from the mega-apps they use daily, so I can borrow a familiar mental model?" | Mobbin (big consumer apps), web. Think: the patterns billions of people are already trained on |
| 3 | **Ecosystem & aspirational** | "Who else — *not necessarily a competitor* — solves a structurally similar problem brilliantly, in an adjacent domain?" | Mobbin + web across adjacent domains |
| 4 | **Design trends** | "What visual / graphic directions are current for this kind of product — where is the aesthetic going?" | Dribbble, Behance, Awwwards (via web search + browser), plus Mobbin for shipped-product aesthetics |

### Pillar 1 — Direct competitors
Same problem, same audience. Start from Mobbin, but also run a web search to make sure you've named the *actual* direct competitors in this market, not just whoever happens to be in Mobbin. This is the "table stakes" pillar: it tells the user what their audience will expect by default.

### Pillar 2 — Million-user apps (familiar conventions)
This is the pillar people forget. The goal is **not** competitors — it's the giant consumer apps the audience uses every day (Instagram, WhatsApp, Gmail, Spotify, Uber, banking super-apps, Notion, etc.) that have *trained the audience* on a convention you can reuse. Borrowing a familiar pattern lowers the learning curve to near zero. Pick apps **relevant to the specific pattern** being designed: researching an onboarding? → how the mega-apps onboard. A feed? → how the feeds the audience already scrolls are built. A number-heavy dashboard? → how consumer finance apps the audience already trusts present numbers. Always tie the pick back to "your audience already knows this from X."

### Pillar 3 — Ecosystem & aspirational
Broaden past direct competitors into the **surrounding ecosystem and adjacent domains** that share a structural challenge. Example — a **bank** app: pull from fintech, government / public-sector services, big-data and analytics tools, dashboards and any "lots of numbers, high trust, high stakes" product. The lens is *structural similarity*, not category. These are where the genuinely fresh, best-in-class ideas usually come from.

### Pillar 4 — Design trends (VISUAL direction, **not** more features)
This pillar is about **how it LOOKS**, not what it does. Surface ~8–10 distinct current **visual / graphic directions** for this kind of product, across the visual dimensions: **UI style** (glassmorphism, neo-brutalist, soft/airy, editorial, retro), **color & gradients**, **typography** (display faces, oversized headings), **hero / cover & graphic language**, **illustration & imagery style**, **layout density & grid**, **motion cues**.
**Source it from Dribbble / Behance / Awwwards FIRST** — those are the design-trend sources — and **capture the real shots via the browser** (they have no MCP). Mobbin is only a *secondary* "how the trend looks once it ships" check for this pillar, never the primary source.
> ⚠️ **Do not drift into feature inspiration here — the #1 failure of this pillar.** If a shot is interesting because of *what the screen does* (a filter, a map, a trust badge, a dietary chip), that is pillars 1–3, not pillar 4. A pillar-4 pick earns its slot on **aesthetic direction alone** — type, color, composition, graphics, illustration. If your pillar 4 ends up as more product screenshots of features (e.g. a row of Mobbin app screens), you did it wrong: go back to Dribbble / Behance / Awwwards for actual design-trend shots in the project's niche. Label each as a *direction* and name the borrowable visual element.

## Step 0 — Always interview first

Before any search, **ask the user** (even if the project folder seems to tell you — the user asked to always be asked). **Ask through the interactive question UI** (the structured multiple-choice question card — `AskUserQuestion`), **not** as a plain-text list. Give concrete options for each (with example screens/platforms/audiences so the user just taps) and let them type anything else via the free-text option. This is a hard requirement — the user asked for the questions to come through that UI.

Ask the four **choice** questions in one interactive card (project, audience, screen, platform). The two inputs below that can't be multiple-choice — user research and the board URL — come as the card's free-text option or a one-line follow-up:

1. **Project / topic** — what is being designed, and what does the product do?
2. **Audience / persona** — who uses it; their sophistication and what apps they already live in (this directly feeds pillar 2).
3. **The specific screen / pattern / flow** being researched — onboarding, a dashboard, an AI-generation flow, a checkout. Be concrete; vague briefs produce vague boards.
4. **Platform** — mobile / web / both (so Mobbin `platform` is set correctly).
5. **User research — the engine of "why this is good for us."** Ask, in words close to these: *"מה כבר ידוע לנו על המשתמשים? מה הם מחפשים, מה הכאבים שלהם, איך נראה מסע המשתמש שלהם?"* Invite the user to **paste one or more links** (a research doc, interview notes, a journey map, a PRD) **or** to write it as free text. If links are given, **open and read them** (built-in browser / web-fetch; for a Figma/FigJam/Notion/Docs link use the matching tool, not a raw fetch) and pull out the concrete **pains, needs, and journey moments**. This is optional but high-leverage — see the note just below.
6. **Where to place the board** — the Figma / FigJam file URL (or create a new file). A URL is free-text, so ask it as the free-text option or a one-line follow-up.

If the user already gave some of this in their request, confirm the gaps rather than re-asking everything. Do not start searching until the pattern is concrete.

### Why the research question matters most

"מה רואים" (what you see) is objective and easy. **"למה טוב לנו" (why it's good for us) is where the research lives** — and it's only valuable when it's tied to a *real* user pain, need, or journey moment, not generic praise ("nice clean layout"). The research from question 5 is the lens: every reference you keep should earn its place by answering **"which known pain / need / journey stage does this help solve?"** Distil what the user gave you into a short working list of **pains → needs → journey stages**, and carry it into Step 2 (selection) and Step 3 (the caption).

If the user has **no research to share**, say so plainly: the "why for us" lines will be **assumption-based** (grounded in the persona, flagged as a hypothesis), and offer to sharpen them later once real research exists. Don't fake confidence the research doesn't support.

## Step 1 — Research each pillar

Default target: **5 references per pillar** (≈20 total). You have a standing license to go **beyond 5** for any pillar when you see real research value — e.g. the trend pillar splits into several distinct visual directions worth showing, or a pillar surfaces a cluster of ideas the user would clearly benefit from. When you expand, say why in one line. Don't pad to hit a number.

For each pillar:

- **Mobbin first for pillars 1–3** (`mcp__mobbin__search_screens`, `platform: 'web'` or `'ios'` for mobile-first, `mode: 'deep'`, `limit: 6-8`). Run several angled queries **in parallel**. Vary the query per pillar — pillar 2 queries name the mega-apps; pillar 3 queries name the adjacent domains. **Pillar 4 is the exception: start from Dribbble / Behance / Awwwards (browser-captured), not Mobbin** — Mobbin screens are shipped products (features), which is the wrong register for a visual-trend pillar.
- **Web search** to (a) name the real players a database might miss, and (b) reach sources with no MCP. Always web-search pillar 1 (confirm the true direct competitors) and pillar 4 (current Dribbble/Behance/Awwwards directions).
- **Dribbble / Behance / Awwwards have no MCP here.** Use web search to find specific shots/pages, then open them in the browser to capture or download a real image. If a site blocks image embedding, fall back to a browser screenshot of the shot, or — last resort — a link-only card, and say so.
- **Flows, not only screens.** `mcp__mobbin__search_flows` returns a real *multi-screen flow* (a whole sequence), not a single still. Use it to find the one winning flow (see Step 3), and any time a *sequence* teaches more than a single frame.

**Flows-only mode:** if the user explicitly asks for **flows** (not "references" / "screens" / "inspiration"), the *entire* output is flows — use `search_flows` for every pillar and embed the multi-screen sequences, never single shots. Otherwise the board is single-screen references **plus the one winning flow** (Step 3).

Keep for every pick: the product/source name, a one-line hook, the real screenshot image URL (Mobbin short URL, or a downloaded image path), and the source link.

## Step 2 — Select the strongest

Apply benchmark criteria (from the `ux-strategy:competitive-analysis` methodology):

1. **Pain / journey fit** — does it help solve a *known pain, need, or journey moment* from the Step 0 research? This is the primary lens: a beautiful reference that answers no real pain doesn't earn a slot. (When there's no research, this softens to persona fit, flagged as a hypothesis.)
2. **Pattern fit** — does it map directly to the screen/flow in the brief?
3. **Persona match** — would *this* audience actually use / recognize it? (Decisive for pillar 2.)
4. **Aesthetic match** — does the visual register fit what's being built? (Decisive for pillar 4.)
5. **Novelty vs. what's already on the board** — don't repeat a pattern another pick already shows.

Mark the single best pick in each pillar as `⭐ anchor`.

## Step 3 — Build the FigJam board

Use the **`figma-inspiration-board`** skill for the screenshot *mechanics* only — download each shot locally, `upload_assets` in batches of 5 (max count per call), and set each image as a `FILL` fill on a `figma.createFrame()`. That skill's card + sticky + connector *layout* is **not** the target here. **Use the item anatomy below instead** — it matches the reference inspiration board the user works from.

### Item anatomy — the required format

Every reference on the board is a **vertical stack of three elements**, nothing more:

```
┌─────────────────────────────────────────┐
│  ⭐ ProductName — what it is             │  ← TITLE (text, bold ~Inter 72, full column width)
│                                         │     ⭐ prefix only on the pillar's anchor pick
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│                                         │
│          [ REAL SCREENSHOT ]            │  ← IMAGE FRAME (createFrame + image FILL)
│                                         │     portrait for mobile, landscape for web
└─────────────────────────────────────────┘

┌─────────────────────────────────────────┐
│  מה רואים: <one-line description of the  │  ← CAPTION (single text note under the image)
│  screen / pattern / visual>.            │
│  למה טוב לנו: <why it helps OUR product, │
│  tied to the persona + the screen being │
│  designed>.                             │
│  🔗 <source link>                        │
└─────────────────────────────────────────┘
```

So each item = **title → screenshot → caption**. No rounded-rect cards, no connector arrows. The caption is one text block, and it always carries the two things the user asks for every time:

1. **מה רואים / What you see** — a plain, factual read of what's in the shot (the layout, the pattern, the visual move).
2. **למה זה טוב למוצר שלנו / Why it's good for our product** — the payoff, phrased against a **specific user pain, need, or journey moment** from the Step 0 research (name it: *"פותר את הכאב ש…"* / *"עונה על הצורך ל…"* / *"בשלב X במסע"*). Anchor it to the real project, persona and screen — not generic praise; a reference that maps to no known pain is just a pretty picture. If there was no research, write this as an explicit hypothesis (*"הנחה: אם המשתמש מתקשה ב…"*) rather than stated fact. Sharpen the line per pillar:
   - **Pillar 1** — is this a *table-stakes expectation to meet*, or a *gap to beat*?
   - **Pillar 2** — name the mega-app: "האודיינס כבר מכיר את זה מ-<app>" / "your audience already knows this from <app>."
   - **Pillar 3** — the *transferable structural idea* ported from the adjacent domain.
   - **Pillar 4** — the *visual direction* and which elements are borrowable (type / color / density / motion).

Write the caption in the **user's language** (Hebrew for this user), matching the tone of their existing board.

### The one winning flow (⭐ — a full sequence, not a single shot)

A single screen shows *a* moment; a **flow** shows the *thinking* — how a product actually walks the user through the job, step by step. On every board, pick **exactly one** standout flow (the one you'd genuinely tell the user to go study) and give it the spotlight:

- Pull the **actual multi-screen flow** with `mcp__mobbin__search_flows` — not a single `search_screens` shot. Download and embed **its screens in sequence, left → right**, so the row reads as steps 1 → 2 → 3 → ….
- Give it its **own strip**, set apart from the four pillars — a section titled `⭐ Winning flow — <Product>: <flow name>`, placed **first on the board** (above the pillars) so it reads as the headline, not buried in a pillar.
- Caption it once, under the strip, with **the approach** (what the flow does, step by step, in a line or two) **and why it fits** — tied to the Step 0 pain / journey, exactly like every other caption.
- Earn it, don't force it: choose the single best flow on merit, and if **nothing** clearly stands out, skip the winning flow entirely rather than inventing one.

(In **flows-only mode** this isn't "one" — every pillar is built from flows. The winning-flow strip is for the normal single-screen board, where it's the one sequence worth the extra space.)

### Board structure & layout

Four **sections, one per pillar**, each clearly titled, so the four read as a set (give each a distinct fill tint):

- `פילר 1 — מתחרים ישירים / Direct competitors`
- `פילר 2 — אפליקציות ענק (קונבנציות מוכרות) / Million-user apps`
- `פילר 3 — אקוסיסטם והשראות / Ecosystem & aspirational`
- `פילר 4 — טרנדים עיצוביים / Design trends`

Add a short header note at the top of each section stating the question that pillar answers, so the board explains itself to anyone who opens it later.

Lay items as **columns in a row**, left → right, with the three elements stacked per column. Working coordinates that match the reference (section-local): columns spaced **~2800px** apart (title/image/caption ~2280px wide); within a column, **title at y≈980**, **image frame at y≈1250** (~1700 tall for portrait mobile), **caption at y≈3100**. Five items per row; if a pillar earns more than 5, start a second row below (repeat the y-offsets lower down). Mark the pillar's best pick with a `⭐` on its title.

> ⚠️ **FigJam placement gotcha — keep every image, title and caption *inside* its section (learned the hard way).** A node that is a child of a FigJam `SECTION` is positioned in coordinates **relative to that section's origin**, not absolute canvas coordinates. Three rules follow:
> - **Use section-local offsets for every child.** Each title, image FRAME and caption gets small offsets *within* its section (the `~2800px` columns and `y≈980 / 1250 / 3100` rows above are these local offsets, e.g. x ≈ 150 / 2950 / 5750 / 8550). **Never** set a child to an absolute canvas value like `-31350` — it will push the whole column tens-of-thousands of px off the colored section frame while still looking internally aligned. That is exactly the "images floating outside the section" bug.
> - **Create each pillar/flow section at the page top level** (`figma.currentPage.appendChild(section)`), then set the *section's own* `x`/`y` to the absolute canvas slot. **Do not nest** the pillar sections inside another section (e.g. a parent "UI Hacking" section): nesting stacks the parent's offset on top of the child coordinates and throws everything off by the parent's origin. To make the board *sit visually inside* an existing big section, place the top-level sections at absolute coordinates within that section's bounds — as **siblings, not children**.
> - **Verify before reporting.** Read each image's `absoluteBoundingBox` and confirm it falls *inside* its section's `absoluteBoundingBox`. The `get_screenshot` endpoint does **not** reliably render programmatically-added IMAGE fills (they show blank even when correct), so trust the bounding-box check, not the screenshot, and have the user confirm in real Figma. If children sit far from the section frame, they were given absolute coords or the section is nested — fix by setting children to section-local offsets (`child.x -= section.x; child.y -= section.y` if they were set absolute) and/or reparenting the section to the page.

## Step 4 — Report back

When the board is built, reply with:
- The **FigJam board link**.
- A short **top-picks summary**: the `⭐ anchor` from each pillar and the single sharpest takeaway, so the user gets the headline without opening the board.
- Any **gaps or fallbacks** — a pillar where Mobbin was thin, a trend shot that could only be linked, a source that blocked embedding.

## Step 5 — Offer another round

A board is a starting point, not a finish line — the user often wants to go deeper on one angle. **After reporting, ask through the interactive question UI (`AskUserQuestion`) whether to pull more directions / inspirations, and let them pick _which pillar(s)_** — set `multiSelect: true` with the four pillars as options plus an **"כל הפילרים / All pillars"** option. (If they want more only on, say, pillar 4, they tick just that.)

For each chosen pillar, run **another round**:
- Search **fresh angles** you haven't used — new Mobbin queries, new adjacent domains, different Dribbble directions. **Don't repeat** a product or pattern already on the board; the whole point is new ground.
- Apply the same selection lens (pain/journey fit first), download, upload, and **append to that pillar's existing section as a new row below the current one** — reuse the row y-offsets, shifted down by one row-height (see the layout note: "if a pillar earns more than 5, start a second row below"). Grow the section's height to fit.
- Keep the `⭐ anchor` as-is unless a new pick genuinely beats it — then move the star and say why.

Then **offer again**. Repeat until the user says they're done. Each round is cheap relative to its value, so keep the loop open rather than assuming the first pass was enough.

## Edge cases & fallbacks

- **Mobbin returns little for a pillar** — widen to web search and name real products, then pull their shots via browser. Don't leave a pillar empty; say if a pillar is genuinely sparse and why.
- **Dribbble / Behance blocks the image** — browser-screenshot the shot, or fall back to a titled link card. Never silently drop it.
- **No Figma file given** — ask; create a new FigJam file only once the user confirms where.
- **Scope too broad** ("inspiration for my app") — push back to Step 0 and pin down one screen/pattern. Four pillars across a vague brief produces four vague sections.
- **Mobile vs web** — match Mobbin `platform` to what's being designed; a mobile app should pull `ios` shots, not web.
