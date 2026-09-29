# The Half-Second

The screen does not persuade you. It moves you, and you write the story
afterwards.

A body registers a stimulus about 150 ms after it lands. The person becomes
aware of it about 500 ms after. Everything a feed is engineered to do happens
inside that gap. What arrives on the far side as *my decision*, *my mood*, *my
sense of where I stand* is downstream of a body that was already moved, and the
narrating mind then supplies a reason, feels the reason as the cause, and
judges everyone else by the same folk theory.

This instrument lets you operate that chain, stage by stage, on a synthetic
feed and a synthetic body. It never tells you to log off. It shows you the
half-second.

## What it does

Seven stations down one page, with the apparatus pinned beside them: a phone
running a twelve-card feed, a line figure with live gauges and an unnamed
intensity bloom, and a narration panel that answers *why did you keep
scrolling?* twice.

1. **The feed.** Toggle the engineering and every card names its technique and
   the sense it addresses. The red count is a hail.
2. **The senses.** Hover a card and its channel lights on the body. Swap the
   cultural preset and the same cue lands at a different weight.
3. **The body moves.** Gauges and bloom go live. Tap the same card five times
   and it habituates; pull to refresh and watch what gets served instead.
4. **The half-second.** A scrubbable timeline. Below 500 ms the body is live and
   the narration is blank. Scrub back and the words vanish while the gauges
   stay.
5. **The narration.** What you would say beside what the trace shows. Then a
   stranger's angry reply, and the trace behind that too.
6. **Downstream.** Standing, threat and agency meters that sediment and do not
   reset. A norm dial. *Put it down*: the gauges recover in ninety seconds, the
   meters never do.
7. **The loop closes.** The four weights your session moved, and the sentence
   they amount to. Zero them and the feed goes flat.

A coda on language: the same bloom under a coarse and a granular vocabulary.
The bloom does not change. The sentence does.

## The data is invented

Twelve cards, one good card, one synthetic body, three cultural presets and two
vocabularies, all in the `SPECIMEN` constant at the top of the script. No real
person's feed, body or words are in the file. The gauges are illustrative, the
numbers are round, and the page says so.

## What it reads and writes, and what never leaves the machine

Nothing leaves the machine. No backend, no account, no analytics, no telemetry,
no storage. State lives in memory and is forgotten on reload. There are no
third-party requests at all: the two typefaces are served from `fonts/`.

## Run

```bash
open index.html
```

or, if you would rather serve it:

```bash
python3 -m http.server 5252
```

## Status

Prototype, September 2026. The design is in `SPEC.md`. Every citation behind it
is listed in `docs/SOURCES.md` and none has been checked against a primary
source yet.
