# The Half-Second

> **Status: built as a prototype, 30 Sep 2026.** `index.html` implements every station below with two deviations: the narration panel sits under the body in the sticky apparatus rather than pinned to the window bottom, and the per-card dwell/skip/tap log stands in for a full event trace. Written from Param's notes
> (affect, senses, real-but-abstract, folk psychology, texture, interpellation,
> the incentives gripe). Every citation is from memory and unverified. Run
> `verify-sources` before any of it is published.

An interactive explainer of how screen-mediated life engineers affect, and how
engineered affect then runs decision, self-image and self-conception, before
the person has had a thought about any of it.

## The claim

The screen does not persuade you. It moves you, and you write the story
afterwards.

Affect is autonomic, pre-subjective, visceral: intensities that move a body
before there is an "I" to be moved. The body registers a stimulus roughly 150
ms after it lands; the person becomes aware roughly 500 ms after. Everything
the feed is engineered to do happens inside that gap. What arrives on the far
side as *my decision*, *my mood*, *my sense of where I stand*, is downstream
of a body that was already moved, and the narrating mind then does what
narrating minds do: it supplies a reason, feels the reason as the cause, and
judges everyone else by the same folk theory.

Corollaries the instrument has to land:

1. **Inputs are bodily, not informational.** A red badge, a haptic buzz, a
   face with eyes, a slow-loading spinner: these address the senses, and the
   senses are not neutral. They are textured by history. Red means something
   because of a hundred years of red meaning something.
2. **Emotion is affect captured and named.** The intensity comes first; the
   word ("anxious", "left out", "fired up") is fitted to it after the fact,
   from whatever vocabulary the person has to hand. Language and expression
   are the last stage, not the first.
3. **The loop closes through other people.** The world acts on you through
   the world's perception of you (Cooley's looking-glass self, 1902,
   *unverified*). The platform's model of you *is* the world's perception of
   you, operationalised and fed back as the next card. Shared norms decide
   which comparisons hurt.
4. **Folk psychology is the alibi.** "I kept scrolling because I wanted to
   see what she posted" is not a lie. It is a confabulation that feels like
   introspection. The same folk theory that misreads the self is what the
   person uses to judge others' beliefs and intentions.
5. **An installed affect is not an incentive you must obey.** The engineer's
   framing (Eyal, *Hooked*; Fogg's behaviour model, *unverified*) treats the
   hook as a rational incentive and treats obeying it as normal, even noble.
   The instrument's stance is the opposite: seeing the mechanism confers no
   obligation to it.

The instrument argues this by letting the reader operate the chain, stage by
stage, on a synthetic feed and a synthetic body. It never tells them to log
off. It shows them the half-second.

## Why this is a CAPP instrument

Post-phenomenology's core claim is that technologies mediate perception before
they mediate action. This is that claim at the smallest usable scale: one
stimulus, one body, one narration. It sits next to `nervous-system-sandbox`
(the body as readable instrument) and upstream of `terra-cognita` (what the
sediment of these loops looks like at age 38). It is the missing first link:
how a single card becomes a reinforcement.

## The reader's journey (five minutes, guided)

The page is one long vertical signal chain, top to bottom, seven **stations**.
Each station is one panel, one sentence of copy, one thing to poke. A guided
mode walks the reader through with a single next button. A free mode lets
them poke anything.

The reader is always looking at three things at once, pinned:

- **Left: the feed.** A synthetic scroll of about twelve cards.
- **Right: the body.** A line-drawn figure with a handful of live gauges.
- **Bottom: the narration.** What "you" would say happened, in first person.

The stations change which part of the chain is lit and what the reader can do.

### Station 1: The feed (input)

The synthetic feed scrolls. Nothing else. Then a toggle, **show the
engineering**, overlays annotations on each card naming the technique it
carries:

| Technique              | Cue on the card                              | Sense it addresses          |
| ---------------------- | -------------------------------------------- | --------------------------- |
| variable reward        | pull-to-refresh, uneven spacing of "good" cards | anticipation, motor        |
| the hail               | red badge, "3 people mentioned you"          | vision (luminance, colour)  |
| social comparison      | a peer, a number, a metric you are below     | vision, then norm           |
| outrage seed           | a claim framed as a threat to your group     | threat detection            |
| the face               | eyes looking at the camera                   | gaze detection              |
| autoplay               | motion starting without a tap                | peripheral vision           |
| the buzz               | a haptic pulse on the frame                  | touch                       |
| the spinner            | a delay held just long enough                | anticipation                |

The hail is Althusser's interpellation ("Hey, you there!", 1970,
*unverified*): the badge constitutes you as its addressee before you decide
anything. Copy on this station says so in one line.

**Poke:** toggle the overlay. Drag the card order and watch the reward schedule
label update (fixed, variable). Nothing downstream fires yet.

### Station 2: The senses (transduction)

Each cue, when hovered, lights the sensory channel it travels down on the
body figure: retina, cochlea, skin, vestibular, proprioception (neck flexion,
the RSI Guy tie-in). A small note under each channel: **texture has a
history**. Red as alarm, a face as a demand, a buzz as a summons: these are
learned, cultural, and old. The instrument shows a swatch and, for two of them,
the one-line history (the red of stop signs; the buzz of a pager).

**Poke:** swap the cultural preset (two or three: e.g. "grew up with pagers",
"grew up with WhatsApp") and watch the same cue route to a different intensity.
This is the cultural-mediation lever, kept deliberately small.

### Station 3: The body moves (autonomic)

The gauges wake up. Heart rate, skin conductance, pupil, breath, neck angle,
and an **anticipation** bar standing in for dopaminergic prediction. A card
lands, and within a beat the gauges move. No label, no "I", no emotion word.
A timestamp runs: t = 0 to t = 500 ms.

The affect is drawn not as an emotion icon but as an **intensity field**: a
diffuse bloom on the figure that has magnitude and location but no name. This
is the real-but-abstract: the body is concrete, the affect is abstract, both
are real (Massumi, *Parables for the Virtual*, 2002, *unverified*).

**Poke:** tap any card and watch the bloom. Tap the same card five times and
watch the bloom shrink (habituation) and the reward schedule compensate by
serving a stronger card. The engine adapts; that is the point.

### Station 4: The half-second

The whole station is one horizontal timeline, scrubbable.

```
0 ms          150 ms                       500 ms
|  stimulus   |  body has moved            |  "you" arrive
|             |  gauges up, bloom present  |  narration begins
|<----------- the platform works here ----------->|
```

Libet's readiness-potential gap (1983, *contested and unverified*) via
Massumi's "missing half second" (*The Autonomy of Affect*, 1995,
*unverified*). The copy says one thing: the person is late to their own
reaction, and the feed is designed for the part they are late to.

**Poke:** scrub. At 150 ms the body panel is live and the narration panel is
blank. At 500 ms the narration panel fills in. Scrub back and the words
disappear while the gauges stay up. That single motion is the argument.

### Station 5: The narration (contra folk psychology)

The narration panel asks: *why did you keep scrolling?* Two answers appear
side by side.

- **What you would say.** "I wanted to see what she posted." "I was just
  checking." "That take was wrong and someone had to say so."
- **What the trace shows.** Card 4 seeded threat, conductance still elevated,
  three skips under a variable schedule, the hail at card 7 constituted you
  as addressee, dwell doubled on the comparison card.

Nisbett and Wilson (1977, *unverified*) and Gazzaniga's interpreter
(*unverified*) in one line: the first answer is not dishonest, it is what
introspection produces. Then the turn: this is the same theory you use on
other people. **Poke:** a small panel, *judge someone else*. It shows a
stranger's behaviour (they posted the angry reply) and asks you to pick their
reason. Then reveals their trace. Same mechanism, different body.

### Station 6: Downstream (decision, self-image, self-conception)

Three meters that drift over a session and do not reset when a card leaves
the screen:

| Meter              | Moves on                            | Reads as                        |
| ------------------ | ----------------------------------- | ------------------------------- |
| standing           | comparison cards, under a norm      | "I'm behind" / "I'm fine"       |
| threat             | outrage seeds, in-group framing     | "the world is hostile"          |
| agency             | hails answered vs ignored           | "I choose" / "I'm summoned"     |

Under the meters, the **norm dial**: the reader picks which shared norm the
feed is scored against (income, followers, fitness, being informed). The same
card moves *standing* by a different amount under each norm. Comparison hurts
only relative to an expectation, and the expectation is social.

Then the incentives gripe, as copy: the engineer calls the meter an incentive
and says obeying it is rational. The instrument says the meter is an installed
affect and declines to call obeying it anything.

**Poke:** run the feed for twenty cards in free mode and watch the meters
sediment. Then hit **put it down**. The gauges take about ninety seconds of
page time to return; the meters do not return at all. That asymmetry is
what "sediment" means, and it is the handoff to `terra-cognita`.

### Station 7: The loop closes (the model of you)

A small panel titled **what it thinks you are**. Every dwell, skip, tap and
scroll-back in the session has been updating a crude profile: threat-
responsive, comparison-responsive, hail-responsive, with weights. The next
card served is chosen from those weights. The reader sees that the feed they
scrolled at Station 1 was already this.

Copy: *the world acts on you through the world's perception of you. Here is
the perception.*

**Poke:** edit the weights by hand and watch the feed reorder. Zero them and
the feed goes flat and dull. That dullness is the honest baseline the whole
page was measured against.

### Coda: language and expression

One final panel, not numbered. The same intensity bloom from Station 3 is
shown once more, and the reader picks a vocabulary: **coarse** (good / bad /
meh) or **granular** (twelve words). The bloom does not change. The narration
does. Emotional granularity (Barrett, *unverified*) as the one lever the
person actually holds: not what moves them, but what they can say about it,
and therefore what they can do next.

## Modes

- **Guided.** Seven stations, one next button, a sentence of copy each. Under
  five minutes. This is the default for a stranger.
- **Free.** Every poke live at once, the feed runs, the meters drift, the
  profile updates. For someone who wants to feel the engine adapt.
- **Reset.** Everything to zero. No state survives a reload.

## The specimen

Synthetic, as with every instrument here. A `SPECIMEN` constant holds:

- twelve feed cards, each tagged with technique, sensory channel, intensity
  magnitude and location, and a norm sensitivity vector;
- a body baseline (resting gauges, habituation rate, recovery half-life);
- three cultural presets that remap cue to intensity;
- two vocabularies;
- a bank of folk-psych narrations and matching traces.

No real person's feed, body or words are in the file. A stranger can open it
and understand it without supplying their own life. Bringing your own feed is
a later feature and, if it ever happens, reads an export from disk and sends
nothing anywhere.

## Non-goals

- Not a detox app. No streaks, no pledge, no screen-time number, no shame.
- Not a neuroscience simulator. The gauges are illustrative, the numbers are
  round, and the copy says so once, plainly.
- Not a catalogue of dark patterns. Eight techniques is enough to make the
  argument; a hundred makes a wiki.
- Not a self-report instrument. It never asks the reader how they feel.
- Not built against a real platform. No brand names, no stolen UI.

## Build constraints (house rules)

- One `index.html`. Inline CSS and JS. No build step, no server, no account.
- No third-party requests at all. Fonts self-hosted in `fonts/` (note:
  `nervous-system-sandbox` currently pulls Google Fonts and Fontshare and is
  out of policy; do not copy its head).
- SVG for the body figure and the intensity bloom. No canvas library needed.
- Light and dark from one token set. `taste` and `anti-slop-ui` before any UI.
  Hard bans hold: no Inter, no gradients, no card grid, no emoji icons, no
  `transition: all`.
- Motion is the argument here, so reduced-motion must still work: the
  timeline scrub and the bloom degrade to stepped states, not to nothing.
- Local port when served: 5252.
- Public or not is Param's call. Default private until he says otherwise.

## Repo shape

```
half-second/
  index.html        the instrument, SPECIMEN constant at the top
  fonts/            self-hosted faces
  README.md         opens with the claim, then run instructions
  SPEC.md           this file
  AGENTS.md         repo contract, spine format
  CLAUDE.md         @AGENTS.md
  docs/
    SOURCES.md      every citation, with verification status
```

## Open questions for Param

1. The notes say **Edie Sedgwick** next to "texture has context and history".
   Texture is Eve Kosofsky Sedgwick (*Touching Feeling*, 2003, *unverified*),
   who also co-wrote the Tomkins revival with Adam Frank (1995). Edie Sedgwick
   works as a *specimen* instead: a self manufactured by being looked at,
   pre-digital. Which did you mean, or both?
2. Is the incentives paragraph yours or a quotation? If quoted, it needs a
   source before the page carries it.
3. Does the instrument end at the coda (language), or does it hand off
   explicitly to `terra-cognita` with a link and a sentence?
4. Guided mode copy: your voice or the house voice? If yours, `param-voice`
   before drafting.

## Sources named above, all unverified

Massumi 1995 *The Autonomy of Affect*; Massumi 2002 *Parables for the Virtual*;
Libet 1983 (readiness potential, contested); Tomkins (affect theory); Sedgwick
& Frank 1995 *Shame in the Cybernetic Fold*; Sedgwick 2003 *Touching Feeling*;
Althusser 1970 (interpellation); Cooley 1902 (looking-glass self); Nisbett &
Wilson 1977 *Telling More Than We Can Know*; Gazzaniga (the interpreter);
Barrett (constructed emotion, granularity); Damasio (somatic markers);
Bourdieu (habitus); Eyal *Hooked*; Fogg (behaviour model); Schüll *Addiction by
Design*. Check each against a primary source before it appears in the page or
in anything published.
