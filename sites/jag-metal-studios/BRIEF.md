# JAG Metal Studios: brief

Interviewed. The client's answers are quoted exactly as given. Everything marked
**Authored** is a decision I made inside the brief.

## The business

> "A high-end luxury Ironworks business that creates Railings, Staircases,
> gates, and fences. The buyers of this service are developers and homeowners
> looking for high-end custom metalwork."
>
> "A minimal simple website where customers can learn more about the company and
> see our work."

- **Believe by the end** (Authored): this is the studio you bring in when the
  metalwork has to be the best thing in the house.
- **One action** (Authored): *Start a project*. The same label is used in the
  nav, the hero and the close.

## The eight topics

1. **Vibe**: "Simple and modern - architectural design."
2. **Journey**: "Who we are, What we do, Examples of what we have done and
   contact us."
3. **Energy**: "in the top of the site, building up to our work (product
   pictures)". Calm at the top, rising to the Work section.
4. **Feeling**: "High-end quality of metalwork. built for those that love their
   home and want the best for it."
5. **The one thing**: "scroll smoothly and transition. have almost like a
   storytelling feel."
6. **Range**: "clean simple, straight to the point." The aesthetic family is
   premium-minimal and architectural.
7. **World** (Authored, since it wasn't asked): distinct scenes, not one
   continuous flight. The story is told in chapters: *drawing, steel, work,
   commission*.
8. **Assets**: the client also supplied a reference layout,
   `JAG_Ironworks_Website.pdf`. It has a cream ground, black iron, bronze labels
   and a bold sans with a serif. It also supplied facts: **architect-led design**
   for **South Florida** homes, fabrication by **trusted partners**, powder
   coating for the coastal climate, a homeowner/builder split, and a four-step
   process. The site adopts those facts, sections and that look. A logo exists in Figma, but the export was blocked by the
   client's Figma plan limit, so the site uses a typeset wordmark for now.
   Product photos are "awaiting". No other constraints.

## Reference adoption

- Copy is taken from the reference wherever it exists. The hero, approach, paths,
  process, builders and contact copy are the client's own words.
- Name: the client stated **JAG METAL STUDIOS**, but the reference says *JAG
  Ironworks*. The site uses the stated name. **To confirm.**
- Testimonials and the work filter chips from the reference are left out on
  purpose. The quotes are placeholders, and inventing them is not allowed. The
  filters fight the scroll-driven sketch-to-photo sequence. Both can be added
  once real quotes exist and there are enough projects to filter.

## Story spine (Authored)

Every piece of custom ironwork starts as a line drawing and ends as steel. The
page follows the same path. It opens on an architect's elevation that draws
itself as you scroll, the drawing turns into solid iron, the four disciplines are
each shown as drawings, and the Work section is where real photography replaces
the line.

## Feeling curve

| Act | Feeling | What causes it |
|---|---|---|
| 1 Hero / Drawing | Calm, curious | A stair-rail elevation in pencil drawing itself under your scroll, then turning to black iron |
| 2 Approach + paths | Trust | Architect-led statement on a dark band, then a clear homeowner or builder choice |
| 3 What we design | Rising interest | Sideways travel through five disciplines, each drawing inking into iron as it arrives |
| 4 Process | Confidence | A rule draws across Measure, Design, Fabricate and Finish & install as you read |
| 5 Selected work (peak) | Desire | Each project opens as its sketch, then the finished piece wipes over it. This is the largest span on the page |
| 6 Builders + contact | Resolve, ease | A builder offer on a dark band, then "Let's draw something." and a short form |

**The peak**: "the drawing turned into the actual railing, and then the photos
just kept opening up." This lives in act 5, and the process act before it is quieter.

**Tell-someone sentence**: "It's the site where you watch the drawing become
the steel."

**Authored silence**: the opening grid before the first line draws (roughly the
first 8% of act 1) is intentional, not dead scroll.

## Score

Grammar: **architectural monograph**: a drawing set that turns into built
work. Nav: a quiet frosted bar with a serif monogram and an underlined
"Start a project", per the reference. Hero device: an SVG line elevation drawn by scroll that fills into solid
iron (the signature move). Close: a pinned contact sheet with an inline form.

| Act | Device | Why |
|---|---|---|
| 1 Drawing | `pin` + scroll-drawn SVG + parallax planes | The signature move. Line to iron in front of the visitor |
| 2 Approach + paths | `flow` + `data-sc-in` | Trust is earned in prose, and the visitor picks a path |
| 3 Disciplines | `pan` | Sideways travel reads as a range of options |
| 4 Process | `flow` + scroll-drawn rule | Read like a document, with a quiet line drawing across it |
| 5 Work | `pin` + nested `reveal` (5vh span) | Sketch to finished piece: the emotional peak |
| 6 Builders + contact | `flow` close with form | The page stops performing and gets useful |

Families: pin, flow, pan, reveal, plus the custom draw. No family appears twice
in a row. No video. The page is 14.8 viewport-heights long.
