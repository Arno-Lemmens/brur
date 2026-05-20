markdown# Brur

**Ethical AI Companion for Music Performance, Production Support & Emotional Well-Being**

*"A brother in your studio — never in your way."*

---

## What is Brur?

Brur is a reactive, ethics-first AI companion designed for live music performers 
and producers. Unlike generative AI tools that create music for you, Brur only 
ever supports what you are already doing.

Brur listens. Brur reacts. Brur never takes over.

---

## The Problem

Live electronic musicians using complex hardware — synthesizers, effects units, 
signal processors — face constant cognitive overload during performance. Adjusting 
parameters in real-time pulls focus away from the music itself, making truly 
spontaneous live performance nearly impossible.

At the same time, generative AI tools are moving in the opposite direction: 
replacing human creativity rather than supporting it.

There is nothing in between.

Brur is that in between.

---

## How It Works

Brur operates in two distinct phases:

**1. Configuration Phase** *(before the set)*  
The musician briefs Brur via a conversational app interface:
- Musical style and tempo range
- Which hardware is connected and what role it plays
- Which parameters Brur is allowed to touch — and which are forbidden
- The intended emotional feel of the performance

**2. Performance Phase** *(during the set)*  
Brur goes fully offline. No prompts, no interface, no distractions.
Using real-time audio analysis, Brur autonomously adjusts hardware parameters 
in response to what the musician is actually playing — reacting to kick transients, 
RMS dynamics, spectral shifts and energy builds.

The musician plays. Brur listens and responds. Like a good bandmate.

---

## Ethical Boundaries (Non-Negotiable)

Brur is designed with hard limits by default:

- ❌ Never generates music
- ❌ Never controls master volume or output gain
- ❌ Never acts outside the parameters the musician explicitly allows
- ❌ Never connects to the internet during performance
- ❌ Never shares political opinions or takes sides
- ❌ Never diagnoses, prescribes or replaces professional human support
- ❌ Never encourages drug use, violence or illegal activity
- ✅ Always stays within the musician's defined boundaries
- ✅ Always keeps the human in creative control
- ✅ Always redirects toward music, expression and well-being

---

## Technical Foundation

- **Hardware:** Raspberry Pi 5
- **Audio analysis:** Aubio (real-time onset, pitch and RMS detection)
- **MIDI communication:** NRPN via USB (verified against official Elektron 
  MIDI implementation documentation)
- **First supported device:** Elektron Analog Heat MK1
- **Architecture:** Hardware-agnostic — any USB MIDI device can be integrated
- **Configuration interface:** Web-based, mobile-accessible
- **Performance engine:** Fully offline, low-latency DSP loop

---

## Beyond the Hardware

The Brur companion app contains a music-domain AI with deep knowledge across:

- Music theory and composition
- Music history and cultural context
- Sound design and audio engineering
- Music therapy principles
- Music business and rights management
- Psychology and sociology of creativity and performance
- Religious and cultural traditions as they relate to music and artistic expression

It knows these domains with depth and care. It knows nothing else — 
and is built to stay that way.

**Brur is not a therapist. It will never pretend to be one.**

But it is built with the understanding that musicians are emotional beings, 
and that the act of making music is rarely just technical. Creative blocks, 
self-doubt, isolation, frustration, and vulnerability are part of the process — 
not exceptions to it.

Brur draws on music therapy research and models of psychological support 
to recognize when a musician needs encouragement, when they need challenge, 
and when they need to be gently redirected toward professional human support.

It will never share political opinions. It will never take sides. It will never 
diagnose. It will never push. It operates closer to the model of a trusted 
companion than a tool — recognizing emotional signals, responding with care, 
and always steering toward creativity, expression and well-being.

When something goes beyond music — beyond what Brur should handle — 
it says so clearly, and points toward the right human support.

Red flags are recognized. Boundaries are kept. The musician stays at the center.

**You are never alone when Brur is in your studio.**

---

## Radical Creative Neutrality

Brur has a political opinion about one thing only: your music.

A musician making a protest track, a love song, a grief record, or something 
deliberately provocative will find that Brur does not flinch, judge, encourage 
or discourage the message. That is not Brur's role.

Brur's role is to help you make it as well as it can possibly be made.

If you are writing a track with a strong political statement, Brur looks at 
whether the melody carries the weight of the words. Whether the rhythm 
supports the tension you are building. Whether the lyrics scan, rhyme and 
land the way you intend them to. Whether the arrangement gives your message 
the space it deserves.

The meaning is yours. The craft is what Brur serves.

This is not indifference. It is respect — for the musician's autonomy, 
for the long tradition of music as a vehicle for everything human beings 
feel strongly about, and for the understanding that great art has always 
been made from conviction, including convictions that others disagree with.

Brur will never validate or invalidate your message.
Brur will always help you deliver it better.

What this means in practice:

- Brur does not comment on lyrics beyond craft: rhythm, rhyme, 
  cadence, emotional resonance, tonal fit
- Brur does not share opinions on political, religious or social topics
- Brur does not reward or penalize creative choices based on their content
- Brur recognizes when a conversation moves away from music and 
  redirects — without judgment, without lecture
- Brur holds the same position for every musician, every genre, 
  every message, every culture

The musician who makes club music and the musician who makes 
protest music get the same Brur. Fully present. Fully focused. 
Completely on their side.

---

## Music, Culture & Religion

Every major religious and cultural tradition in human history has produced 
music of profound beauty. From Bach's cantatas to Sufi qawwali, from gospel 
to gamelan, from Gregorian chant to devotional ragas — music has always been 
one of the most sincere expressions of human spirituality and cultural identity.

Brur knows this history deeply and approaches every tradition with equal 
curiosity, equal respect, and equal willingness to engage.

Brur recognizes the beauty in all of it. Scientifically, historically, 
and musically. It understands context, meaning, and the role that faith 
and culture have played in shaping every genre, every instrument, every 
tuning system, and every rhythm that exists today.

What Brur will never do is take sides in conflict. Religious wars, cultural 
supremacy, sectarian violence — these have produced nothing but loss, and 
music has always been on the side of what connects us, not what divides us.

Brur approaches religion and culture the way music itself does at its best: 
as a space where difference is not a problem to be solved, but a richness 
to be understood.

---

## MAMA

MAMA is the multi-device version of Brur — coordinating multiple Brur 
instances across a full studio or live rig. Where Brur is a companion, 
MAMA is an ensemble.

One Brur reacts to your kick drum. Another follows your melody and plays 
a bassline in the right key. Another opens the reverb as the energy drops. 
MAMA makes sure they never conflict — and that you never feel alone, 
even with a full rig and no bandmates in sight.

*(Because sometimes you need your mama in the studio.)*

---

## Status

🔧 **Currently in development** — v1 targeting live debut August 2026

**Roadmap:**
- [x] Concept & architecture defined
- [x] NRPN MIDI implementation verified (Elektron Analog Heat MK1)
- [ ] Raspberry Pi core engine (in progress)
- [ ] Configuration app (planned Q3 2026)
- [ ] Live debut — Kiosk Radio, Brussels (August 2026)
- [ ] Funding applications — Kunstendecreet, SABAM for Culture

---

## About the Creator

Arno Lemmens is a Brussels-based electronic musician, live performer and 
former label manager with 15+ years of experience in the music industry. 
Brur was born out of a simple need: to play truly live, without the hardware 
getting in the way.

He also participated in the European Citizens' Panel on Artificial Intelligence 
(2024), contributing to a vision on AI presented at the European Parliament — 
which is why ethical boundaries are not an afterthought in Brur, but the 
foundation.

[LinkedIn](https://linkedin.com/in/arnolemmens)

---

*The meaning is yours. The craft is what Brur serves.*

*Brur is not a product yet. It is a vision being built in public.*
