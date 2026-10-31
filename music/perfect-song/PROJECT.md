# The Perfect Song — Project File
Status: **v0.2 — Purpose locked, Phase 2 (Reference DNA) open**

---

## 0. LOCKED BRIEF
- **Effect:** calm or anxious → excited and motivated
- **Listener:** Ahmad (personal). Possible public release later.
- **Sonic world:** techno + Gregorian chant + sampled ethereal / angelic female vocals
- **Method:** pull the best elements from Ahmad's reference songs into one original track

---

## 1. RESEARCH BRIEF — How sound acts on the body

Evidence is graded: **[STRONG]** = repeated peer-reviewed findings · **[MODERATE]** = some studies, smaller samples · **[WEAK]** = popular claim, little or poor evidence.

### A. Arousal vs mood: the key insight for this brief
- **Two separate dials:** Emotion runs on **arousal** (energy) and **valence** (positive or negative) (Russell's circumplex model).
  - Calm → excited means **raising arousal**.
  - Anxious → excited means **keeping arousal high but flipping valence** from negative to positive. Anxiety and excitement share the same physiology. Reappraising anxiety as excitement improves performance (Brooks 2014, Harvard).
- **Design consequence:** the track must work for both starting points.
  - Open with a **mid-energy, slightly tense, spacious section**. It meets an anxious listener without startling a calm one.
  - Then **raise the energy and brighten the harmony** together.

### B. Tempo and rhythm
- **Entrainment [STRONG]:** Heart rate, breathing and movement drift toward the beat.
- **Motivational tempo band [STRONG]:** Karageorghis (Brunel research, 20+ years): the motivational sweet spot is **~120–140 BPM**, peaking at ~125–135 for most people. Melodic and peak-time techno sits exactly here.
- **Gradual tempo or energy rise [MODERATE]:** The rise pulls the body upward (the iso principle in reverse). Suno can't automate a BPM change, so the "rise" is built through **density, filter openings and layering**, not literal tempo.
- **Groove [STRONG]:** Witek (2014): a **moderate amount of syncopation** produces the strongest urge to move and the most pleasure. Too straight is boring, too complex is confusing. Offbeat hats and syncopated percussion over a four-on-the-floor kick hit the sweet spot.

### C. Bass and power
- **"Power songs" [MODERATE→STRONG]:** Hsu et al. (2015, *Social Psychological & Personality Science*): **music heavy in bass made people feel more powerful and dominant** and made them act more assertively.
- **Physical bass [STRONG]:** Low frequencies (40–100 Hz) are felt in the body, not only heard. A rolling bassline gives the physical push.

### D. Build-ups, drops and chills
- **Anticipation → release [STRONG]:** Salimpoor (2011): dopamine is released **during the anticipation** (caudate) and again **at the peak** (nucleus accumbens). The techno build → break → drop structure is close to a direct dopamine engine.
- **Chills triggers [STRONG]:**
  - a sudden texture change, such as a solo voice entering
  - a new layer coming in, such as a choir
  - a dynamic surge
  - an unexpected harmonic shift
  - a high voice emerging over a low drone

  Angelic female vocals over Gregorian chant over a techno drop combines several of these at once.

### E. Gregorian chant
- **Modal harmony:** Chant uses church modes. **Dorian** is minor but with a hopeful raised 6th, the ideal "anxious → uplifted" mode. **Mixolydian** is bright and driving. Aeolian is darker.
- **Long phrases [MODERATE]:** Bernardi (2001, *BMJ*): reciting chant-like prayer (the Ave Maria) and mantras slowed breathing to ~6 breaths per minute and synchronized cardiovascular rhythms. Use chant in the **intro and the breakdown** to settle and center the listener before the lift.
- **Male low choir:** sits in the chest and resonance range, which grounds the listener and lends an ancient, sacred weight.

### F. Ethereal / angelic female vocals
- **Register contrast:** Pitch height reads as "uplift, light, transcendence". Placing a **high female voice over a low male chant** gives maximum contrast, and the contrast drives chills.
- **Texture:** breathy, airy, long reverb tails, wordless vowels ("ah", "oo") or sparse words.

### G. Harmony and tension
- **Consonance and reward [STRONG]:** Resolved harmony triggers reward. Tension that is built and then resolved is the engine.
- **Key move [MODERATE]:** shifting from minor (Aeolian/Dorian) in the intro to brighter (Dorian or relative major) at the peak mirrors anxiety → motivation.

### H. Loudness and production
- **Dynamic contrast [MODERATE]:** The drop only hits if the breakdown is genuinely quiet. Avoid a flat wall of sound.
- **Hearing safety [STRONG]:** Long listening above ~85 dB causes damage. Motivational music tempts people to play it loud.

### I. Frequency claims
- **432 Hz / 528 Hz / binaural beats [WEAK]:** Optional aesthetic layers added in post-production. Suno cannot do them.

### J. What kills the effect (avoid list)
Avoid aggressive distortion that pushes toward anger instead of drive, cluttered mids, a monotone loop with no arc, a drop with no build, abrupt jarring cuts in the intro, harsh hyper-compression, and lyrics of despair.

### K. Suno constraints
- **Style field:** ~1000 characters in v4.5/v5.
- **Exclude Styles field:** used for negative prompts.
- **Lyrics field:** use metatags such as `[Intro] [Build] [Drop] [Breakdown] [Choir] [Chant] [Female Vocal] [Instrumental] [Silence] [Outro]`.
- **Chant text:** works best written out in Latin.
- **Not controllable:** exact BPM curves, tuning and binaural beats. These need a DAW.
- **Real artists and songs:** they can't be named, and copyrighted audio can't be uploaded. References are translated into **descriptive elements**.
- **Public release:** Suno's paid plans grant commercial rights to generated output. Confirm the current terms before release.

---

## 2. OUTLINE — Build phases

| # | Phase | What we decide | Status |
|---|---|---|---|
| 1 | **Purpose** | Calm or anxious → excited and motivated | ✅ LOCKED |
| 2 | **Reference DNA** | Ahmad's songs + the exact element he loves in each | 🔵 OPEN |
| 3 | **Sonic physics** | BPM, key/mode, groove, bass character | ⚪ |
| 4 | **Arc and structure** | The journey through the song: intro → builds → breakdown → drops → outro, and length | ⚪ |
| 5 | **Vocal architecture** | Chant (male choir, Latin), angelic female layer, lead voice yes/no | ⚪ |
| 6 | **Message** | Theme, language (Latin / English / mix), lyrics | ⚪ |
| 7 | **Sound design and mix** | Synths, kick, sidechain, reverb space, dynamics | ⚪ |
| 8 | **Compile** | Final Suno Style + Exclude + Lyrics fields | ⚪ |
| 9 | **Test and refine** | Generate variants, measure heart rate and your felt motivation (1–10), chills count, iterate | ⚪ |
| 10 | **Release prep** (optional) | Originality check, Suno commercial terms, mastering, distribution | ⚪ |

---

## 3. MAP — Body-effect levers → song decisions

```
CALM/ANXIOUS ──► EXCITED/MOTIVATED
│
├── AROUSAL ↑ ──┬── TEMPO ────── entrainment ───────── 120–140 BPM techno pulse
│               ├── DENSITY ──── energy build ──────── layers + filter opens
│               ├── BASS ─────── felt power ────────── rolling sub/bassline
│               └── GROOVE ───── urge to move ──────── moderate syncopation
│
├── VALENCE ↑ ──┬── MODE ─────── dark → hopeful ────── Aeolian/Dorian → bright Dorian
│               ├── HIGH VOICE ─ uplift/transcend ─── angelic female layer
│               └── WORDS ────── meaning ───────────── triumph, rising, light
│
├── DOPAMINE ───┬── BUILD ────── anticipation ──────── risers, snare rolls, tension
│               ├── DROP ─────── peak release ──────── full kick + bass + choir
│               └── CHILLS ───── texture surprise ─── solo voice entry, choir swell
│
└── CENTERING ──┬── CHANT ────── breath slowing ────── intro + breakdown
                └── DRONE ────── grounding ─────────── low choir / pad bed
```

---

## 4. EVOLVING SUNO PROMPT — v0.2

**Style field:**
```
melodic techno, Gregorian chant, ethereal angelic female vocals, [BPM TBD] BPM, [KEY/MODE TBD], deep male monastic choir, rolling hypnotic bassline, driving four-on-the-floor kick, syncopated percussion, cathedral reverb, slow-building tension, euphoric drop, dark-to-uplifting progression, cinematic, spacious, [REFERENCE ELEMENTS TBD]
```

**Exclude Styles field:**
```
distortion, harsh, aggressive, screaming, rap, trap, dubstep wobble, cheesy EDM, pop vocal, autotune, abrupt transitions, cluttered
```

**Lyrics field (structure skeleton):**
```
[Intro – Gregorian Chant, no drums]
[Build – kick enters, filter opening]
[Female Vocal – ethereal]
[Drop]
[Breakdown – choir and angelic vocal, no kick]
[Build]
[Drop – full choir + female vocal + bass]
[Outro]
```

---

## 5. DECISION LOG
| # | Decision | Value |
|---|---|---|
| 1 | Effect | Calm/anxious → excited and motivated |
| 1b | Audience | Personal, possible public release |
| 1c | Genre world | Techno + Gregorian chant + angelic female vocals |
| 1d | Frame | Not religiously driven |
