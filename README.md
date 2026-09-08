# Cronologia — Mário Ferreira dos Santos

An open, source-referenced chronology of **Mário Ferreira dos Santos
(1907–1968)**: Brazilian philosopher, translator, journalist and publisher of
his own books; author of the unfinished *Enciclopédia das Ciências Filosóficas
e Sociais* and of the system he called *filosofia concreta*; a documented
presence in the anarchist Centro de Cultura Social in São Paulo, and the
subject of a dated, partisan and disputed revival from the 1980s onward.

**Site:** <https://cronologia.github.io/marioferreirasantos/> · part of the
[Cronologia](https://cronologia.github.io/) project family.

## Method

- `data/chronology.json` is the single source of truth; every fact and event
  carries `sources[]`; contested characterizations are attributed to their
  authors and never asserted in the site's own voice. See `AGENTS.md` for the
  subject-specific rules (the family-derived catalogue, the contested volume
  count, the per-work year discordances, the COF citation discipline) and
  `context.md` for orientation and the access register.
- The build is a zero-dependency Node compiler from
  [cronologia/core](https://github.com/cronologia/core)'s template:
  `node scripts/validate-data.js && node build.js && node --test`.
- English is authoritative. `data/i18n/{es,pt}.json` are **empty on purpose**:
  no translation has been produced yet, and an honest empty cache makes the
  completeness suite report exactly how many strings would render untranslated
  rather than letting a stale dictionary pretend to cover them.

## What the dataset says, and does not

- **The volume count of the *Enciclopédia* is contested**, and every figure on
  the site is attributed: 52 (Olavo de Carvalho), 45 (English Wikipedia),
  "cerca de 50" (Moura & Azevêdo), and a family-derived catalogue numbering
  I–XLVIII including unpublished manuscripts. **No source reached by this
  project supports the "100+ volume plan" that circulates online**, and the
  site asserts no total of its own.
- **Per-work years are slippery.** He self-published and re-edited constantly;
  where the catalogue and the Portuguese Wikipedia disagree, both years are
  recorded and neither is adopted. On *Filosofia Concreta* the admirer site
  contradicts its own catalogue page, and the dataset says so.
- **Three checked absences**, each with its method: no entry in the CPDOC/FGV
  *Dicionário Histórico-Biográfico Brasileiro* (the search's positive control
  was an unrelated "Ferreira dos Santos" born 1894); no confirmed estate site;
  no 2007 centenary event found.
- **Reception is a lane, not a verdict.** "Silenced", "solitary philosopher",
  "absolute isolation" and "deliberate independence" all appear — each with the
  person who said it and the year they said it.

## Status

Rebuilt and authored 2026-09-08 from verified research of 2026-08-12. Live:
37 events across four storyline lanes (life · anarchism · works · reception),
10 facts, 11 figures, 11 organizations, 6 disambiguations and 24 references.

Open work: the Spanish and Portuguese dictionaries (195 translatable strings,
currently zero); a full census of the COF transcription corpus, which this
subject saturates and which the dataset therefore touches at exactly two dated
entry points; and four sources that resisted capture — the É Realizações blog
and its "Nota", the Vide Editorial listing, and Vita's 1953 review and 1968
obituary in *Revista Brasileira de Filosofia*, which are still known only
through quotation.
