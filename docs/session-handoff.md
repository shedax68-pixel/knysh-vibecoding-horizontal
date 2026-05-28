# Session handoff

## Published site

GitHub Pages:

https://shedax68-pixel.github.io/knysh-vibecoding-horizontal/

Latest cache-busted check URL used:

https://shedax68-pixel.github.io/knysh-vibecoding-horizontal/?v=df2a250

## Latest committed production changes

- Hero uses the clean XP-style project desktop visual, not the lying stickman variant.
- Hero right visual has a large yellow "Папка проекта", blue motion paths, and role-based cursor agents:
  - дизайн агент
  - финанс. агент
  - менеджер агент
  - юрист агент
  - креатор агент
  - программист агент
  - разработчик агент
- Removed the stray white rectangle from the lower-right of the hero visual.
- CSS is cache-busted from `index.html` with `styles.css?v=20260527-3`.
- Speaker slide:
  - role under "Александр Кныш" is forced into exactly 3 lines via three spans;
  - logo wall is aligned higher, starting near the speaker-card row.
- Price slide:
  - added exclusion note: AI subscriptions, server rental, and possible other expenses are not included.

## Useful local files

- `docs/hero-slide-visual-brief.md` - original visual brief for the first slide.
- `docs/archive/prototypes/html/hero-slide-new-options.html` - two hero prototype directions.
- `docs/archive/prototypes/images/prototype-hero-agents-folder.png` - selected direction for the production hero.
- `docs/archive/prototypes/images/prototype-hero-lying-stickman.png` - rejected/alternate lying-stickman direction.

## Notes for next session

- If GitHub Pages appears visually broken, check whether the HTML and CSS are from different cache generations.
- Increment the CSS query string in `index.html` after any CSS changes.
- Do not assume `?v=` on the page URL invalidates linked CSS unless the CSS link itself also changes.
