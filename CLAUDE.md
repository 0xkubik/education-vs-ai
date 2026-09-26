# education-vs-ai

## About
Статья про то, как образование борется с ИИ вместо того, чтобы интегрировать его. Текущие методы борьбы с ИИ в образовании бесперспективны — вместо борьбы надо учиться подстраиваться под мир с ним. Автор на 2 курсе магистратуры в 2026 году, его просят сдавать работу в виде рукописного конспекта; до этого он больше 3 лет программировал своими руками и сам внутренне протестовал, когда всю работу велели делать через ИИ. Полные тезисы — в `resources/tesises.md`.

Замысел по структуре: в начале — поныть и описать наглядно ситуацию с образованием в России; в конце — предложить свой вариант того, как адаптировать всё образование, начиная с детсада и заканчивая получением учёной степени и дальше.

Надо рассмотреть, как другие страны и учреждения встраивают ИИ в обучение.

## Publication
- **Where:** Хабр; its requirements are in docs/ (none supplied yet)
- **Tone:** conversational — `tone-conversational`
- **Final file:** md — article.md is the artifact

## For the agents
Автор пишет статью сам, без сроков, для Хабра. Хочет, чтобы она была сильной: не просто с его размышлениями, но и с источниками, подкрепляющими факты. Хочет, чтобы она набрала много на Хабре и привлекла внимание. Соавторов и запретных тем не названо. Source material: `resources/tesises.md` — the author's theses; `resources/research-ai-education-2026.md` — research notes.

Со слов автора, не проверено: «насколько я знаю, в вузах Сингапура уже есть проприетарная нейронка, которая помогает студентам». Не подавать как факт, пока не найден источник.

## Layout
- `article.md` — the article.
- `docs/` — what the venue supplied: requirements and limits. Read before writing or building.
- `media/<format>/` — figures, one folder per format: `excalidraw/` sources, `png/` exports.
- `resources/` — material for writing: theses, research, references.
- `scripts/` — the layouter's scripts. Outputs land where they belong: exported diagrams in `media/png/`.
- `Makefile` — the main commands: `make png` exports the diagrams. The layouter keeps it current.
