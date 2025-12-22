---
title: "1. Synthesizers"
subtitle: "Synthesizers and subtractive synthesis"
authors: MUS1703, Week 1
description: "This page takes you through Week 1 of the course."
edit_url: null
---


![synth](figures/cover/synth.jpg)

## Have you ever used a synth?

This week introduces the fundamentals of **synthesizers** and **subtractive synthesis**. We cover history, core components (oscillators, filters, envelopes, LFOs), signal flow, and hands-on patch creation. The aim is to give you conceptual grounding and practical skills to design and document original sounds.

```{admonition} Question
:class: question
Can you define the term "synthesis"?
```

# Learning outcomes

- **Define** basic terms: synthesis, oscillator, waveform, filter, envelope, LFO.  
- **Explain** the signal flow of a subtractive synth and how filters shape timbre.  
- **Create** at least three distinct patches (bass, pad, lead) using subtractive techniques.  
- **Document** and **reflect** on sound-design choices in a short written report.

---
## Definitions

- **Synthesis:** Generating sound electronically or digitally.  
- **Subtractive synthesis:** Start with harmonically rich signals (e.g., saw or square) and remove frequencies with filters to shape sound.  
- **Oscillator (VCO):** Produces periodic waveforms (sine, triangle, sawtooth, square).  
- **Filter (VCF):** Cuts or boosts frequency bands; **low-pass** filters are central to subtractive synthesis.  
- **Envelope (ADSR):** Controls amplitude or filter cutoff over time—Attack, Decay, Sustain, Release.  
- **LFO:** Low-frequency oscillator used for slow modulation (vibrato, tremolo, filter wobble).

---
:::{aside}
:::{figure}
:label: moog synth
![](https://upload.wikimedia.org/wikipedia/commons/f/f8/1st_commercial_Moog_synthesizer_%281964%2C_commissioned_by_the_Alwin_Nikolai_Dance_Theater_of_NY%29_%40_Stearns_Collection_%28Stearns_2035%29%2C_University_of_Michigan.jpg)

The first commercial Moog synthesizer (1964).
::::::

## Historical context

From early modular synthesizers (Moog, Buchla) to modern software synths, subtractive synthesis has been foundational in electronic, pop, and film music. Key artists to listen to: Kraftwerk, Wendy Carlos, Vangelis, Depeche Mode, and seminal modern producers who use subtractive synths extensively.

---

## Practical signal flow

Typical subtractive chain:
1. **Oscillator(s)** generate waveform(s) → mix for harmonic content  
2. Optional **sub-oscillator** / octave detune for thickness  
3. **Filter** (commonly low-pass) removes harmonics and with **resonance** emphasizes cutoff region  
4. **Envelope** applied to amplitude and/or filter cutoff for dynamic shape  
5. **LFOs** and additional modulators for movement  
6. **Effects** (reverb, delay, distortion) for spatialization and color

:::{tip}
Use a bright waveform (saw) + low-pass filter with modest resonance for a classic subtractive sound.
:::
---

## In-class demo

Step-by-step demo (10–15 minutes):
- Start with a single sawtooth oscillator at 0 detune.  
- Route to a low-pass filter (cutoff 50–70%, resonance 10–30%).  
- Apply envelope to filter: A=10–30ms, D=100–400ms, S=30–70%, R=300–800ms.  
- Add amplitude envelope: quick attack, short decay for percussive bass.  
- Add gentle LFO to pitch or filter for subtle motion.

Software suggestions: Ableton Live (Operator, Analog), Logic (ES2), NI Massive/Monark, Serum, Arturia plugins, or any subtractive soft-synth.

---

# Lab work
Do these in your DAW/synth.

1. **Bass patch**  
   - Oscillator: saw + octave sub-oscillator  
   - Filter: low-pass, cutoff low, resonance medium  
   - Envelopes: short amp attack, moderate release; filter envelope adds punch  
   - Deliverable: 4-bar loop exported as WAV + patch screenshot

2. **Pad patch**  
   - Oscillators: two detuned saws or triangle + FM for warmth  
   - Slow attack, long release on amp envelope  
   - LFO on pitch or filter for slow movement  
   - Deliverable: 8-bar example + patch screenshot

3. **Lead patch**  
   - Oscillator: waveform with bright harmonics (pulse or saw)  
   - Filter: higher cutoff, higher resonance, shorter filter envelope  
   - Optional: slight distortion or saturation  
   - Deliverable: 8-bar melody + patch screenshot

For each patch, write 3–5 lines documenting signal path and 2 reasons for each major parameter choice.

---

## Assessment questions

- Question: **Can you define the term "synthesis"?**  
  Model answer (short): “Synthesis is the process of creating sound by generating and manipulating electrical or digital signals, often combining oscillators, filters, and modulators to shape timbre and dynamics.”

- Test Yourself:
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
<p><strong>Embedded video:</strong> Kraftwerk — synthesizer demo (YouTube)</p>

<div style="width:100%;aspect-ratio:16/9;">
  <iframe
    src="https://www.youtube-nocookie.com/embed/9B8Xc7CbGs4"
    title="Kraftwerk synthesizer demo — YouTube"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    allowfullscreen
    style="width:100%;height:100%;border:0;display:block;">
  </iframe>
</div>


---

## Advanced topics

- Comparison: Subtractive vs. FM vs. Wavetable synthesis

---

# Task before next week
<u>Assignment 0</u>

Create a short piece or 8–16 bar track (1–2 minutes) that prominently features a patch made with subtractive synthesis.

Deliverables:
- **Audio** file (WAV or MP3)  
- **Patch documentation**: annotated screenshot(s) showing signal flow and key parameter values  
- **Reflection** (100–200 words): explain design goals and how you used subtractive techniques to meet them

---
