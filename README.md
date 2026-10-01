# Build Your Own Cereal Box

Turn your LinkedIn profile into a custom breakfast cereal box, front and back, with a pun-filled name, career badges, a word search, and a mini bio. Works with any AI assistant that can generate images (ChatGPT, Gemini, etc.).

<!-- Add your example images here, e.g. -->
<!-- ![Front of box](examples/front.jpg) ![Back of box](examples/back.jpg) -->

## How to use

1. **Download your LinkedIn profile as a PDF.** On your LinkedIn profile, click **More → Save to PDF**.
2. **Optional:** grab a headshot. A clear, smiling, front-facing photo works best.
3. Open ChatGPT, Gemini, or another assistant with image generation.
4. Attach the PDF (and headshot, if you want).
5. Paste the prompt below and hit send.

## The prompt

```
I'm attaching my LinkedIn profile (PDF) and, optionally, a headshot. Use them to design a custom breakfast cereal box about me, front and back, as two separate images.

STEP 1: PLAN (text only, brief)
Read my profile and propose:
- A cereal name. Make it a pun or riff on my first name, last name, or profession (e.g., "Viet Krispies"). Pick the tone yourself: playful, punny, a little cheeky.
- A mascot or hero image: my headshot if I attached one, otherwise a friendly illustrated character that represents my job.
- A tagline, a "Snap/Crackle/Pop"-style catchphrase based on what I actually do, and a one-line "cereal for a more ___ tomorrow" slogan.
- 3-4 badges from my real career (e.g., employers, roles, skills, awards), styled like "Now with Whole Grains" burst stickers.
- 12-15 words for the back-panel word search, drawn from my profile (companies, skills, tools, places, hobbies).
- A short puzzle/game idea for the back that riffs on my work (e.g., a maze, spot-the-difference, connect-the-dots).
Show me this plan in under 150 words, then continue straight to the images without waiting.

STEP 2: FRONT OF BOX (image 1)
Portrait, 3:4, shot like a real product photo of a cereal box on a kitchen counter. Include:
- Large, bubbly cereal logo with the name, in bold outlined lettering
- Me (from the headshot) or the mascot, smiling, above a bowl of the cereal with a milk splash
- Burst stickers with the catchphrase and 3-4 career badges
- A small slogan at the top corner and "Net Wt 11.5 oz" at the bottom
- Bright, saturated colors in one dominant brand color, with a cohesive playful cereal-box style

STEP 3: BACK OF BOX (image 2)
Same box, same style, same colors. Include:
- Logo and a short banner line (e.g., "Puzzles Today. Brighter Tomorrow.")
- A word search panel using my words from Step 1, with the word list underneath
- A themed game panel (maze or similar) based on my work
- A "[Name]'s Snap-Crackle Career" bio panel: 2 sentences about my background, taken only from my profile, with a small photo or mascot
- Small decorative callouts and a footer slogan

RULES
- Use only facts from my profile. Don't invent employers, titles, or achievements.
- Keep all text short and spelled correctly. Double-check every word on the box before generating.
- Keep it fun and flattering. Never mock me.
- If my headshot isn't attached, don't generate a realistic face. Use an illustrated mascot.
- If any text comes out garbled, regenerate that image before showing it to me.
- Generate the front first, then the back, as two separate images.
```

## Tips

- **Garbled text?** Reply: *"Regenerate the back, fix the spelling and word search letters."* Word-search grids are the hardest part for image models. If it keeps failing, ask for a decorative grid instead.
- **Change the vibe:** add a line like *"Make it retro 80s"* or *"Make it look like a premium organic granola box."*
- **Not happy with the name?** Ask for 5 alternative cereal names, pick one, and regenerate.
- **No headshot?** The prompt falls back to an illustrated mascot based on your job.

## Privacy note

LinkedIn PDFs include contact details like email and phone number. If you're using a personal AI account, consider deleting the contact info page before uploading. Never upload anything you wouldn't want processed by the AI tool you're using.

## Contributing

Got a better version of the prompt, or a great result? Open a PR or issue and share it.

## License

MIT
