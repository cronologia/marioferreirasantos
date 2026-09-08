# context.md — domain background for contributors

Read `AGENTS.md` first (operating rules); this file is orientation.

## The subject

**Mário Ferreira dos Santos** (Tietê, SP, 3 January 1907 — São Paulo,
11 April 1968): Brazilian philosopher, translator and journalist who became his
own publisher. Raised in Pelotas, Rio Grande do Sul, where his Portuguese
father — actor, impresario and a pioneer of Brazilian cinema — had settled the
family in 1909; educated by the Jesuits at the Gymnasio Gonzaga (1916–1924);
law and social sciences in Porto Alegre; journalism and an arrest in December
1930. He translated for the Livraria do Globo in 1943–44 and moved to São Paulo
in 1945 in financial difficulty, where he began frequenting the anarchist
**Centro de Cultura Social**.

From 1946 he published — at first under the pseudonyms **Dan Andersen** and
**Charles Duclos**, then under his own name and through his own houses,
**Editora Logos** and later **Editora Matese**. The *Curso de Oratória e
Retórica* (1953, twelve editions) paid for the philosophy; the philosophy was
the **Enciclopédia das Ciências Filosóficas e Sociais**, opened by *Filosofia e
Cosmovisão* in 1952 and left unfinished at his death. He sold door to door on
credit, refused public posts all his life, and accepted exactly one teaching
position, at the Jesuit Faculdade Nossa Senhora Medianeira, at the end of it.

Why this project exists in the family: he is the philosopher the Brazilian
right's own revival keeps pointing back to, and the `olavo` project keeps
running into him as an object rather than a source. This repo gives that
cross-reference one dated, documented place to point at — and, separately,
gives the anarchist-studies record of him (Ramus, Braga, the Cubero testimony)
a place where it is not overwritten by the revival's framing.

## The three problems that shape every entry

1. **One channel carries the biography.** The daughters' *Monografia sobre
   Mário Ferreira dos Santos* (2001) is the document nearly everything passes
   through — read here via Pachêco's 2019 UFSC dissertation, which quotes
   Ladusãns's declaration of 18 December 1968 (the source of both the birth and
   the death date) and reproduces the Pelotas newspaper evidence that the
   Biblioteca Nacional's geo-block put out of direct reach. The fullest work
   catalogue is on an **admirer-run** site derived from the same family work.
   None of that disqualifies it. It does mean the label travels with it.
2. **The bibliography does not settle.** A self-publisher who re-edits
   constantly leaves a record where the catalogue says 1952 and Wikipedia says
   1954, where *Filosofia Concreta* is 1957 on one page of the admirer site and
   1956 on another, and where multi-volume titles make any count of the
   *Enciclopédia* ambiguous before anyone starts arguing about it. Both years
   go in; neither is chosen.
3. **The reception is a fight.** Jorge Jaime (2000) says a Brazilian
   philosopher was condemned to silence for his whole life; Ladusãns (1968)
   calls him a *filósofo solitário*; Olavo de Carvalho describes a Vico-like
   absolute isolation and a wall of silence — then argues *against* his own
   PCB-retaliation hypothesis and concludes Brazil ignored him because it did
   not understand him. Against all that: Pachêco's "obstinate" refusal of
   public office, a Jesuit faculty post accepted at the end, and hundreds of
   thousands of books sold door to door. Every one of these is somebody's
   sentence, and the site keeps the somebody attached.

## Disambiguations that matter

- **"O homem que foi um campo de batalha" ≠ *O Homem que Nasceu Póstumo*.**
  The first is an **essay**, written 1943 and published 1945 as the preface to
  his Nietzsche translation. The second is a **book**, 1954. Catalogues merge
  them.
- **Two Instituto Cultural Logos.** His own correspondence-course operation
  from 1947, and the present-day admirer-run website that reuses the name. They
  are different entries in `organizations[]` for a reason. **No estate site is
  confirmed to exist**, and the admirer site is not one.
- **The revival is disputed by the people inside it.** Olavo de Carvalho
  organized the 2001 É Realizações edition and is credited by Pachêco with the
  structural map anyone with an overview owes their overview to; Gazeta do Povo
  reported in 2018 that he had been replaced as editor and the treatment
  changed. É Realizações' own "Nota" on the matter is **unread here** — it sits
  behind a bot wall — so its position is characterized in no direction at all.
- **"Ferreira dos Santos" is a common surname string.** The DHBB search
  returned an unrelated man born in 1894; that hit is the positive control, not
  the subject.

## Access register (observed 2026-08-12)

Recorded so the next session does not rediscover it, and so a "not found" here
is read as "not reached" where that is what it means.

| Source | Behaviour |
|---|---|
| `erealizacoes.com.br` | SSL reset / 503 bot-wall — the publisher's blog and its "Nota" both unread |
| `academia.edu`, `philpapers.org` | Cloudflare bot-wall |
| `marioferreiradossantos.com` / `.com.br` | reset, no search presence — **existence unconfirmed** |
| `olavodecarvalho.org` | **hijacked domain serving spam** — cite the IFE mirror or print |
| `repositorio.ufsc.br` | handle pages JS-walled; **PDF bitstreams serve 200 to a browser UA** (strip the multipart MIME) |
| `skoob.com.br` | 403 to the fetch tool, **200 via curl with a browser UA** |
| `videeditorial.com.br` | 403 / 202 challenge |
| `scielo.br` | 403 even with a browser UA this session (contra expectation — retry) |
| `guaiaca.ufpel.edu.br`, `repositorio.unb.br` | 403 / reset |
| `redalyc.org` | JavaScript shell |
| `memoria.bn.gov.br` | **geo-blocked** — the Pelotas press is citable second-hand through Pachêco's annexes |
| `archive.org/wayback/available` | persistent **429** all session; availability checks inconclusive |
| Working | impactum-journals.uc.pt · revistas.pucsp.br · revistas.ufrj.br · repositorio.ufpb.br · dialnet.unirioja.es · faculdadejesuita.edu.br · ife.org.br · institutoculturallogos.com · gazetadopovo.com.br · goodreads.com |

## The COF corpus

He **saturates** the vaulted transcription corpus — queries hit the search
result limit against the index of 2026-08-12 over 1,027 files (cof 589,
olavo-video 237, transcripts 201). The dataset therefore carries **one event
and one fact**, both paraphrase, anchored on two reviewed files: **COF014**
(2009-07-11, *revisada*, which notes that the editions need philological work)
and **COF274** (2014-12-13, *revisada*). A full census is deferred. See
`KEYWORDS.md` before searching, and `AGENTS.md` rule 8 before quoting anything.

## Adjacent Cronologia projects

- `olavo` — Olavo de Carvalho: the reception vector for this subject, dated
  1983–2020, and the source of the COF corpus this dataset cites twice.
- `tfp` — the reference-i18n conventions this dataset follows
  (`publisherNote` carries perspective; `publisher` stays bibliographic).

## Glossary

Use `[[term-id]]` markers for shared terms; run
`node scripts/sync-glossary-terms.js` if a needed term id is missing from the
pinned list. This dataset currently uses none.
