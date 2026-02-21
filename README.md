# CinePrompt — AI Video Prompt Builder

A cinematic AI video prompt studio built in the style of Golden Age Hollywood cinema. Craft perfect prompts for Seedance 2.0, Sora, RunwayML, and Pika with an art-deco film noir interface.

## What It Does

CinePrompt is a single-page web app that helps you build high-quality prompts for AI video generators. Select from:

- **Shot Type** — Wide/establishing, medium, close-up, aerial, tracking, POV
- **Camera Movement** — Static, dolly in, pan, crane, orbit, handheld
- **Lighting Mood** — Golden hour, neon night, foggy, harsh daylight, candlelight, studio
- **Tone & Mood** — Epic, thriller, romantic, comedic, horror, documentary, action, melancholy
- **Color Grade** — Teal & orange, vintage film, B&W, hyper-vivid, cool bleach, natural
- **Target Generator** — Optimizes prompt format for Seedance, Sora, RunwayML, or Pika

The prompt generates automatically as you make selections, with a typewriter animation effect.

## Visual Style

**Golden Age Cinema** — Art Deco Hollywood meets modern UX:
- Warm-black background (#0D0906) with aged parchment cards (#F4E4B4)
- Cinema gold (#C49A2A) typography and accents
- Animated film strip perforations on both edges of the screen
- Director's viewfinder frame showing current shot parameters
- 35mm film strip preview frames for each selection
- Playfair Display serif + Inter sans + Courier Prime monospace

## Why It Was Built

ByteDance's Seedance 2.0 went massively viral in February 2026, generating photorealistic video of Tom Cruise and Brad Pitt fighting on a rooftop from a 2-line prompt. AI video generation exploded onto the mainstream. CinePrompt helps people actually USE these tools effectively by guiding them through the elements of a great cinematic prompt.

## Running

### Docker
```bash
docker compose up -d --build
```
App runs on port 3114.

### Local dev
Open `index.html` directly in any browser — it's fully self-contained with no build step.

## No Backend

CinePrompt is 100% frontend — no server, no API keys, no database. Just HTML/CSS/JS.

## Env Vars

None required.
