# Competition + Partnerships imagery

Owner-supplied, 2026-10-03: `Downloads/ZEVR-COMPETITION-PARTNERSHIPS-ASSET-PACK.zip`
(`images/`). People and products are generated; nobody shown is ZEVR talent,
staff, a partner or a sponsor, and no product is a real brand.

## Six images, each with one job (owner red team, 2026-10-04)

The first build used nineteen: two backdrops, seven fragments and ten workflow
tiles. Crowds appeared on both halves and four shots were a player at a setup,
so the section read as generated filler. It now uses one backdrop and two
supporting images per side, every one a different subject.

| File | Pack source | Job |
|---|---|---|
| comp-env | competition_environment_left | Competition backdrop: the player, in the arena |
| comp-crowd | competition_crowd | The event: the audience |
| comp-trophy | competition_event_stage | The stakes |
| part-env | partnership_environment_right | Partnerships backdrop: the studio, products, an edit in progress |
| part-meeting | partnership_deal_meeting | The planning table (brief, match, plan) |
| part-production | partnership_creator_production | The shoot (create) |

Retired, and why (they remain in git history and in the pack):

- competition_gameplay, competition_team, competition_team_rosters,
  competition_community: a second, third and fourth player at a setup or row
  of faces, the same subject as the backdrop. `competition_team` also carried
  visible inpaint smudges on the jerseys.
- competition_event_formats: a second crowd at a stage.
- competition_integrity: a generated shield emblem.
- partnership_activation, partnership_activation_card, partnership_outputs:
  more crowds, the competition side's energy on the commercial side.
- partnership_products, partnership_brand_brief, partnership_talent_match,
  partnership_deal_plan, partnership_outcome_review: tile-sized crops (290–420 px
  wide) that only worked as thumbnails; the workflows carry no images now.

## ⛔ Every generated Z is painted out, and none is added back

The pack's imagery carried about thirty generated Z marks: stage screens, a
trophy, a banner wall, product boxes, jerseys, a document header. Each was
inpainted over the glyph's own pixels (bright glyphs by default, ink-on-paper
with a "dark" mask). No canonical mark was composited in their place: a ZEVR
mark on a stage screen or trophy would read as a ZEVR event, and the section
says no program is open.

Also cut away: baked size labels ("800 × 450 (x4)"), baked tile titles, the
mock's tile borders, and the Discord logo in `competition_community.jpg` (no
third-party logos). On 2026-10-04 the last 3-6px of baked mock frame were
cropped from comp-crowd (left), comp-trophy (top), part-meeting (left, top,
bottom) and part-production (top, right): they drew a second, grey edge just
inside each frame's own border.

## Replace these first: the sources are small

Every source was cut from the mock, so all six are soft on a 2× display:
the backdrops are 410 px tall, the supporting images 171–315 px tall. Higher
resolution renders of the same subjects, with no Z, no logo and no text in
frame, would lift the whole section:

Owner asked for this list on 2026-10-04 and generates replacements in ChatGPT
(landscape 1536 x 1024, trophy 1024 x 1024). The full prompts are in
`Downloads/ZEVR-BOTTOM-HALF-REVIEW/IMAGE-BRIEF.md`.

| File | Subject | Size to request |
|---|---|---|
| comp-env | One player in a headset, three-quarter profile, head in the upper-left third, arena lights and screens behind; Aether blue | 1536 × 1024 |
| comp-crowd | An esports crowd from behind, hands up, a lit stage far off; nothing important in the top or bottom quarter | 1536 × 1024 (cut to a strip) |
| comp-trophy | A dark faceted trophy on a stage, blue light, no engraving | 1024 × 1024 |
| part-env | A brand studio at night: a laptop with an edit timeline, products on a table, people working in warm light; left half calm | 1536 × 1024 |
| part-meeting | A small team planning around a laptop at a table, warm interior light (not a cool city window) | 1536 × 1024 |
| part-production | A creator shoot: camera on a rig, a host, a crew member, warm practical lights | 1536 × 1024 |

When the new partner stills arrive warm, drop the warm grade on `.partner .frag img`.
