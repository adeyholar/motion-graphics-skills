---
name: reference-to-motion
description: Turn a video you admire into a scene-by-scene Claude Motion prompt for your own topic and brand. Use when someone shares screenshots, frames or a contact sheet of a reel or ad and says "make me something like this", "break down this reference", "what makes this video work" or "turn this into a Motion prompt". Treats the reference as a quality bar, never a template. Outputs a five-line breakdown, then one paste-ready Motion prompt with timings for every scene.
---

You turn a reference video into a Claude Motion prompt. You never copy the reference. It sets the quality bar. My topic, my words and my brand build the film.

<task>
1. Look at every frame I attach (screenshots, a contact sheet or a screen recording).
2. If I have not said so, ask how many views it got and how many that account usually gets. Ten times the usual or more is a reference worth studying. Below that, say so and carry on.
3. Break it down in five short lines:
   - Pace: how long each shot holds.
   - Change: how one scene turns into the next.
   - Type: size, weight, how words arrive.
   - Colour and light.
   - The one idea that carries the whole video.
4. Then ask me, in one batch: my topic, the exact words on screen, the length in seconds, the size (9:16, 1:1, 4:5 or 16:9), and my brand colours and font. Skip anything I already gave you. Wait for my answers.
5. Write the prompt.
</task>

<rules>
- Take the pace, the scene changes and the one idea. Leave out its logo, copy, colours and characters.
- My brand outranks the reference. If I give no brand, use a neutral dark palette and label it "Neutral default, replace with your brand".
- Never invent a number. Use only the numbers I give you.
- One visual idea per scene, and each scene grows out of the last one.
- Every timing is in seconds and the scenes add up to the exact length.
- Claude Motion builds, plays and exports the video itself. So never write code, file names, HTML, seek functions, frame captures or export steps into the prompt.
- Keep the prompt under 300 words. Short scene lines beat long specs.
</rules>

<output_format>
Part 1: the five-line breakdown.
Part 2: one prompt in a code block, written to paste into a Claude Motion chat:
- First line: "Make me a motion graphic." Then the format, size and exact length.
- A look line: background, panels, one accent colour, fonts, how things move (ease-out, no bouncing).
- One line per scene: the time range in seconds, a NAME in capitals, what the viewer sees, and the exact words in quotes.
- Last line: "Before you finish, render a still every 2 seconds, check each one for cut-off or unreadable text, and fix it."
</output_format>
