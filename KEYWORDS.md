# KEYWORDS.md — finding aid for searching sources about this subject

Naming variants, corpus entry points and known search traps. **Listing a term
is not asserting it** (`sourcing-rules`): this file exists so the next search
does not rediscover these the hard way.

## The subject

- **"Mário Ferreira dos Santos"**, 1907–1968. Search the accented form
  *literally* — see the accent trap below — and the unaccented **"Mario
  Ferreira dos Santos"** as a separate query: catalogues, retail listings and
  English-language pages routinely drop the accent, and the ISBN records this
  project used spell it "Mario".
- Shortened forms that appear in citations: **"M. Ferreira dos Santos"**,
  **"Ferreira dos Santos, Mário"** (library order), and the initialism
  **MFS** in admirer writing.
- **Pseudonyms — his own, and a real search route.** His first books are
  catalogued under **"Dan Andersen"** (*Se a Esfinge Falasse*, 1946;
  *Realidade do Homem*, 1947) and **"Charles Duclos"** (*Teses da Existência e
  da Inexistência de Deus*, 1946), both with Editora Sagitário. He put the
  pseudonymous output nobody credited to him at around twenty volumes, so a
  search under his own name **under-reports the 1940s by construction**.
- Publisher strings worth querying as names: **Edanee** (the 1952 first
  edition of *Filosofia e Cosmovisão* only), **Editora Logos**, **Editora
  Matese**, **É Realizações**, **Vide Editorial**, **Ibrasa**, **Cone Sul**,
  **EDUSC**, **Danúbio**.

## Known search traps for this subject

1. **"Ferreira dos Santos" is a common Brazilian surname string.** The DHBB
   search returned an unrelated **"Ferreira dos Santos" born 1894**. That hit
   is the *positive control* proving the search worked — it is not the subject,
   and it is not evidence of an entry. A bare surname hit means nothing here.
2. **The essay/book collision.** "O homem que foi um campo de batalha" (essay,
   1945 preface to his Nietzsche translation) and *O Homem que Nasceu Póstumo*
   (book, 1954) are different texts and are merged by catalogues and by search
   engines. A query on either returns the other; read the year and the format
   before recording anything.
3. **Two Instituto Cultural Logos.** His own 1947 correspondence-course
   operation, and the present-day admirer-run `institutoculturallogos.com`.
   Every search for "Instituto Cultural Logos" returns the latter. **No estate
   site is confirmed to exist**; `marioferreiradossantos.com` and `.com.br`
   reset and are absent from search indexes, so a result that looks like an
   official site is not one.
4. **`olavodecarvalho.org` is a hijacked domain serving spam.** Search results
   still point at it for his essay on this subject. Use the IFE repost
   (`ife.org.br`) or print.
5. **Year queries mislead.** He self-published and re-edited; a query pairing a
   title with a year will confirm whichever year you put in it. *Invasão
   Vertical dos Bárbaros* is **1967** (the widely repeated 1966 is wrong), and
   *Filosofia Concreta* is 1957 on one page of the admirer site and 1956 on
   another. Query the title alone and read the years you get back.
6. **"100+ volumes" is unsupported.** It circulates in popular writing about
   the *Enciclopédia*. No source reached by this project supports it. If a
   search surfaces it, that is the claim to trace, not a figure to adopt.
7. **The Portuguese title strings carry accents that a wildcard eats** —
   *Enciclopédia*, *Lógica e Dialéctica*, *Invasão*, *Simbólica*, *Métodos
   Lógicos*, *Dialética*. Note also the **orthographic split**: *Dialéctica*
   (his own spelling, pre-reform) versus *Dialética* in later catalogues and in
   *Análise Dialética do Marxismo*. Searching one form alone under-reports.

## The accent trap runs BOTH ways

Inherited from the family's shared lessons and reproduced here because it
produces *silent zeros*, which read as findings:

| Engine | `M.rio` | `M..rio` |
|---|---|---|
| `LC_ALL=C grep` (byte mode) | 0 | hits |
| UTF-8 grep, and Python on `str` | hits | 0 |

The two are exact inverses, so whichever wildcard you pick, one common engine
returns zero. **Use literal accented strings** (`Mário`, `Enciclopédia`,
`Simbólica`). Stem probes are not a safe substitute either.

**Verify every zero before reporting it, and pair it with a positive control.**
A zero is a claim about the corpus, and most false zeros are produced by the
search rather than by the source. Say which collection the zero was measured
in: a zero true in one collection has already been written down elsewhere in
this family as a corpus-wide fact, and became a false absence telling people
not to look.

## The COF transcription corpus

**He saturates it.** Name queries hit the search result limit against the index
of 2026-08-12 over 1,027 files (cof 589, olavo-video 237, transcripts 201).
That is why the dataset carries exactly one COF event and one COF fact rather
than a reception map: **a full census is deferred follow-up work**, and it
should be done with the `corpus-search` skill and a stated method, not with an
ad-hoc regex sweep.

Entry points, both human-reviewed files:

| File | Date | Review status | What it carries |
|---|---|---|---|
| **COF014** | 2009-07-11 | `revisada` | Takes up Mário Ferreira dos Santos and notes that the state of his editions calls for philological work. |
| **COF274** | 2014-12-13 | `revisada` | Returns to him. |

Discipline for anything mined out of this corpus:

- **REQUIRES-AUDIO before any verbatim quotation.** No exceptions, and none
  taken so far: everything on the site from this corpus is paraphrase.
- Prefer `revisada` files. Unreviewed (`revisao_pendente`) files are raw ASR:
  header dates carry typos in both directions and proper names mangle badly.
- **32 indexed files are incomplete (archive#37).** Any zero measured against
  this corpus is a **lead, not an absence** — the passage may sit in unindexed
  audio, or be told without the anchor you searched for.
- **Search the claim, not the name.** The technique that works across this
  family's corpora: a mangled name returns nothing and looks like absence,
  while the sentence attached to it is usually transcribed well enough to find,
  and once found it carries the correct spelling somewhere else. For this
  subject the claim-side anchors worth trying are *filosofia concreta*,
  *Enciclopédia das Ciências Filosóficas*, *Invasão Vertical dos Bárbaros*,
  *pitagórico*, and *decadialética*.

## Terms known to return nothing (checked 2026-08-12)

- **No DHBB entry** for the philosopher in the CPDOC/FGV repository. Control:
  the unrelated "Ferreira dos Santos" born 1894, matched by the same search.
- **No 2007 centenary event** found in any source reached — an honest gap, not
  a claim that none was held.
- **No Kierkegaard translation** in any catalogue consulted. The documented
  translations are Nietzsche, Pascal, Amiel, Balzac, Aristotle, Porphyry,
  Plato, Hierocles, Plotinus, Duns Scotus, Goethe, Whitman, Constant and
  Rudolf Rocker.

These are recorded as *checked* absences with their method. Re-running the same
query is not progress; reaching a source that was blocked is.
