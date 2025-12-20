---
title: "1. Synthesizers"
subtitle: "Synthesizers and subtractive synthesis"
authors: MUS1703, Week 1
description: "This page takes you through Week 1 of the course."
---

## Have you ever seen a synth before?

This week introduces the fundamentals of **synthesizers** and **subtractive synthesis**. We cover history, core components (oscillators, filters, envelopes, LFOs), signal flow, and hands-on patch creation. The aim is to give you conceptual grounding and practical skills to design and document original sounds.

```{admonition} Question
:class: question
Can you define the term "synthesis"?
```

## Learning outcomes (By the end of Week 1)

- **Define** basic terms: synthesis, oscillator, waveform, filter, envelope, LFO.  
- **Explain** the signal flow of a subtractive synth and how filters shape timbre.  
- **Create** at least three distinct patches (bass, pad, lead) using subtractive techniques.  
- **Document** and **reflect** on sound-design choices in a short written report.

---

## Week plan / Topics

1. Historical context & why synths matter in music production  
2. Basic building blocks: oscillators, waveforms, filter types, envelopes, LFOs  
3. Subtractive synthesis signal path and workflow  
4. Live demo: building patches step-by-step  
5. Lab: guided patch exercises and mini-assignment

---

## Key concepts & quick definitions

- **Synthesis:** Generating sound electronically or digitally.  
- **Subtractive synthesis:** Start with harmonically rich signals (e.g., saw or square) and remove frequencies with filters to shape sound.  
- **Oscillator (VCO):** Produces periodic waveforms (sine, triangle, sawtooth, square).  
- **Filter (VCF):** Cuts or boosts frequency bands; **low-pass** filters are central to subtractive synthesis.  
- **Envelope (ADSR):** Controls amplitude or filter cutoff over time—Attack, Decay, Sustain, Release.  
- **LFO:** Low-frequency oscillator used for slow modulation (vibrato, tremolo, filter wobble).

---

## Historical context (brief)

From early modular synthesizers (Moog, Buchla) to modern software synths, subtractive synthesis has been foundational in electronic, pop, and film music. Key artists to listen to: Kraftwerk, Wendy Carlos, Vangelis, Depeche Mode, and seminal modern producers who use subtractive synths extensively.

---

## Lecture notes — practical signal flow

Typical subtractive chain:
1. **Oscillator(s)** generate waveform(s) → mix for harmonic content  
2. Optional **sub-oscillator** / octave detune for thickness  
3. **Filter** (commonly low-pass) removes harmonics and with **resonance** emphasizes cutoff region  
4. **Envelope** applied to amplitude and/or filter cutoff for dynamic shape  
5. **LFOs** and additional modulators for movement  
6. **Effects** (reverb, delay, distortion) for spatialization and color

Tip: Use a bright waveform (saw) + low-pass filter with modest resonance for a classic subtractive sound.

---

## Demo / In-class exercises

Step-by-step demo (10–15 minutes):
- Start with a single sawtooth oscillator at 0 detune.  
- Route to a low-pass filter (cutoff 50–70%, resonance 10–30%).  
- Apply envelope to filter: A=10–30ms, D=100–400ms, S=30–70%, R=300–800ms.  
- Add amplitude envelope: quick attack, short decay for percussive bass.  
- Add gentle LFO to pitch or filter for subtle motion.

Software suggestions: Ableton Live (Operator, Analog), Logic (ES2), NI Massive/Monark, Serum, Arturia plugins, or any subtractive soft-synth.

---

## Lab exercises (do these in your DAW / synth)

1. **Bass patch (30–45 min)**  
   - Oscillator: saw + octave sub-oscillator  
   - Filter: low-pass, cutoff low, resonance medium  
   - Envelopes: short amp attack, moderate release; filter envelope adds punch  
   - Deliverable: 4-bar loop exported as WAV + patch screenshot

2. **Pad patch (45–60 min)**  
   - Oscillators: two detuned saws or triangle + FM for warmth  
   - Slow attack, long release on amp envelope  
   - LFO on pitch or filter for slow movement  
   - Deliverable: 8-bar example + patch screenshot

3. **Lead patch (30 min)**  
   - Oscillator: waveform with bright harmonics (pulse or saw)  
   - Filter: higher cutoff, higher resonance, shorter filter envelope  
   - Optional: slight distortion or saturation  
   - Deliverable: 8-bar melody + patch screenshot

For each patch, write 3–5 lines documenting signal path and 2 reasons for each major parameter choice.

---

## Assignment (Summative)

Create a short piece or 8–16 bar track (1–2 minutes) that prominently features a patch made with subtractive synthesis.

Deliverables:
- **Audio** file (WAV or MP3)  
- **Patch documentation**: annotated screenshot(s) showing signal flow and key parameter values  
- **Reflection** (200–300 words): explain design goals and how you used subtractive techniques to meet them

Grading rubric:
- Sound design & creativity — 40%  
- Technical documentation & patch screenshots — 30%  
- Musicality & arrangement — 20%  
- Reflection clarity — 10%

---

## Formative assessment questions

- Question: **Can you define the term "synthesis"?**  
  Model answer (short): “Synthesis is the process of creating sound by generating and manipulating electrical or digital signals, often combining oscillators, filters, and modulators to shape timbre and dynamics.”

- Short quiz prompts:
  1. What does a low-pass filter remove?  
  2. Describe what resonance does at the cutoff frequency.  
  3. Give one reason to use an LFO on filter cutoff.

---

## Listening examples & references

Recommended tracks/articles to listen/read:
- Kraftwerk — selected tracks (classic synth timbres).  
- Wendy Carlos — Switched-On Bach (early synth album).  
- Intro reading: Ableton's "Learning Synths" tutorials and Sound On Sound articles on subtraction.  
- Book reference: *The Computer Music Tutorial* — Curtis Roads (for further reading).

---

## Advanced/Optional topics

- Comparison: Subtractive vs. FM vs. Wavetable synthesis  
- Modulation matrices and routing strategies  
- Filter design (analog-modelled vs. digital) and saturation/distortion

---

## Accessibility & inclusivity

- Provide alternative text for screenshots.  
- Use high-contrast colors for step-by-step slides and share DAW project files where possible.

---

## Quick tasks before next week

- Complete at least one lab patch and upload demo + screenshot.  
- Post the 200–300 word reflection to the assignment submission.
