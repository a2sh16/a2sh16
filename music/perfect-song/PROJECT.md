# The Perfect Song — Project File
Status: **v0.1 — Research complete, Phase 1 open**

---

## 1. RESEARCH BRIEF — How sound acts on the body

Evidence is graded: **[STRONG]** = repeated peer-reviewed findings · **[MODERATE]** = some studies, smaller samples · **[WEAK]** = popular claim, little or poor evidence.

### A. Tempo and rhythm (the biggest lever)
- **Entrainment [STRONG]:** The body syncs to an external pulse. Heart rate, breathing and movement drift toward the beat.
- **Slow tempo calms you [STRONG]:** Bernardi et al. (2006, *Heart*): slow music lowered heart rate, blood pressure and breathing rate. Fast tempo raised them. **Silences and pauses relaxed people even more than slow music did.**
- **The 10-second wave [MODERATE]:** Bernardi (2009, *Circulation*): swells and fades (crescendo/decrescendo) on a cycle of about 10 seconds made blood pressure and heart rate rise and fall with them. 10 seconds is ~6 breaths per minute, the resonance rate that gives the best heart-rate variability (HRV) and vagal tone.
- **Gradual slowing [MODERATE]:** In the "Weightless" study (Mindlab 2011, not peer-reviewed), the tempo slid from about 60 to 50 BPM, there was no repeating melody, and the low end was sustained. It reported large drops in anxiety.

### B. Harmony and tone
- **Consonance and reward [STRONG]:** Blood & Zatorre (2001) and Salimpoor (2011): music people love releases dopamine and lights up reward circuits. Musical "chills" peak just after the build-up of anticipation resolves.
- **Dissonance [STRONG]:** Unresolved, harsh dissonance turns on threat and stress areas such as the amygdala and raises arousal. A little tension that then resolves feels good. Constant tension wears people out.
- **Low frequencies and drones [MODERATE]:** Sustained low tones, humming and drones stimulate the vagus nerve through the vibrating larynx and chest, and they ground the listener.
- **The iso principle [STRONG, standard clinical practice]:** Music therapists **start at the listener's current state and then lead it gradually** to the target state. A song that tries to force calm from the first bar does not work as well.

### C. Frequency and tuning claims
- **432 Hz vs 440 Hz [WEAK]:** One small pilot (Calamassi 2019) found slightly lower heart rate. Not replicated. Fine as an aesthetic choice, not proven as medicine.
- **Solfeggio / 528 Hz [WEAK]:** Very little evidence (one small Akimoto 2018 study). Mostly marketing.
- **Binaural beats [WEAK→MODERATE]:** Small effects on anxiety (Garcia-Argibay 2019 meta-analysis). They only work on headphones, and **Suno cannot reliably produce them**. You would add them in post-production.

### D. Loudness and production
- **Over-compressed "loudness war" mixing [MODERATE]:** Causes listener fatigue. **A wide dynamic range (real soft and loud) is more restorative.**
- **Hearing safety [STRONG]:** Long listening above ~85 dB causes damage.

### E. Voice and words
- **Lyrics carry the meaning [STRONG]:** The meaning of the words shifts mood independently of the sound. Words of gratitude, meaning and hope have measurably positive effects.
- **The human voice [STRONG]:** Humans respond more strongly to a voice than to any instrument. A warm, breathy, lower-register voice soothes. A strained, screamed voice alarms.
- **Quran recitation studies [MODERATE]:** Several clinical studies, mostly from Iran, Malaysia and Saudi Arabia, show reduced anxiety and better vital signs when people listen to tajweed. It is melodic voice with no instruments.

### F. The heritage behind your theory
Your theory has a long scholarly history:
- **Al-Kindi (9th c.):** linked oud strings to the four humors and to emotional states.
- **Al-Farabi, *Kitab al-Musiqa al-Kabir*:** wrote on music's power to calm, move or sadden.
- **Ibn Sina:** used music in his medical practice.
- **Ikhwan al-Safa:** taught that cosmic harmony is mirrored in sound.
- **Ottoman bimaristans** (Edirne, Sultan Bayezid II complex, 1488): **treated patients with specific maqamat**, for example Rast for joy and calm, Hijaz for humility, and Saba for spirit and devotion.
- **Western parallel:** Pythagoras and the "music of the spheres".

### G. What makes music "bad" for the body (avoid list)
Avoid sudden jarring transients, constant unresolved dissonance, hyper-compressed walls of sound, a frantic tempo with no release, lyrics of violence, despair or lust, harsh distorted vocals, and engineered addictive hooks with no substance.

### H. Suno constraints
- **Style field:** v4.5/v5 allows up to ~1000 characters.
- **Exclude Styles field:** used for negative prompts.
- **Lyrics field:** accepts metatags such as `[Intro] [Verse] [Chorus] [Bridge] [Outro] [Instrumental] [Humming] [Soft] [Build] [Silence]`.
- **What works roughly:** BPM, key, mood and instrument names.
- **Not controllable in Suno:** exact Hz tuning, binaural beats and precise tempo curves. These need post-processing in a DAW (free option: Audacity).
- **Do not name real artists.** Suno blocks it.

---

## 2. OUTLINE — Build phases

| # | Phase | What we decide | Status |
|---|---|---|---|
| 1 | **Purpose** | The exact effect on the listener (state A → state B) | 🔵 OPEN |
| 2 | **Sharia palette** | Vocals only / vocals + daf / other instruments | ⚪ |
| 3 | **Sonic physics** | BPM and tempo curve, key, mode or maqam, tuning | ⚪ |
| 4 | **Arc and structure** | Iso-principle journey, sections, length, silences | ⚪ |
| 5 | **Message** | Theme, language (Arabic / English / both), lyrics | ⚪ |
| 6 | **Voice** | Gender, register, texture, harmonies, humming | ⚪ |
| 7 | **Production** | Dynamics, low end, space/reverb, mix philosophy | ⚪ |
| 8 | **Compile** | Final Suno Style + Exclude + Lyrics fields | ⚪ |
| 9 | **Test and refine** | Generate, measure HRV/heart rate on your watch, iterate, post-process (432 Hz or binaural if wanted) | ⚪ |

---

## 3. MAP — Body-effect levers → song decisions

```
TARGET EFFECT ──┬── TEMPO ─────── entrainment of heart/breath ── BPM + gradual curve
                ├── 10s SWELLS ── baroreflex / HRV resonance ── dynamic waves, pauses
                ├── HARMONY ───── reward vs threat circuits ── consonance, resolved tension
                ├── MODE/MAQAM ── emotional colour ─────────── Rast / Bayati / Saba / Hijaz / major / Dorian
                ├── LOW END ───── vagal grounding ──────────── drones, humming, warm bass voice
                ├── VOICE ─────── strongest human response ── warm, breathy, unforced
                ├── WORDS ─────── meaning → mood ──────────── dhikr, gratitude, hope
                ├── DYNAMICS ──── fatigue vs restoration ──── wide range, no brick-wall
                └── ARC ───────── iso principle ───────────── meet state → guide → land
```

---

## 4. EVOLVING SUNO PROMPT — v0.1 (skeleton)

**Style field:**
```
[PURPOSE TBD], [GENRE TBD], [BPM TBD] BPM gradually slowing, [KEY/MAQAM TBD], warm intimate vocals, wide dynamic range, gentle swelling and fading phrases, deep sustained low drone, consonant resolved harmony, spacious natural reverb, unhurried, breathing space between phrases
```

**Exclude Styles field:**
```
distortion, harsh, aggressive, screaming, heavy compression, EDM drop, trap hi-hats, abrupt transitions, autotune
```

**Lyrics field:**
```
[Intro]
[Verse 1]
[Chorus]
[Verse 2]
[Bridge]
[Silence]
[Final Chorus]
[Outro]
```

---

## 5. DECISION LOG
| # | Decision | Value |
|---|---|---|
| — | — | — |
