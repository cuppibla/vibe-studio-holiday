# What Gemini sees in the channel's past posters

One line per poster: `- poster: <file> — <two sentences> tags: a, b, c`. Each line becomes a
passage in the RAG corpus beside the comments; read_feedback hands the file name back as
a URL under /static/past/. Regenerate with: python -m agent.platform.rag load --caption

- poster: freezer-snowman.png — A tiny round snowman with big glossy eyes and a red scarf sits in an open white freezer drawer between two ice cube trays, warm string lights behind. Cool freezer light and lavender dusk, cozy and a little mischievous. tags: snowman, freezer, kitchen
- poster: gravy-heist.png — A tiny mouse in a napkin cape freezes mid-reach at an open glowing fridge, a gravy boat on the shelf. Deep lavender midnight kitchen, warm fridge light, playful heist mood. tags: mouse, kitchen, gravy
- poster: sweater-cat.png — A round cream cat judges three small knitted sweaters laid out on a bed: one with a snowflake, one with a pie, one far too small. Candlelight and lavender, deadpan and sweet. tags: cat, sweaters, judging
- poster: gift-penguin.png — A tiny round penguin with big glossy eyes holds a roll of tape and looks at its first wrapped gift, lumpy and crooked with a huge lopsided bow, scraps of paper everywhere. Warm room light, cranberry red and cream, proud and clumsy. tags: penguin, gift, wrapping
- poster: robin-lights.png — A string of warm lights at night with a small round robin hugging one bulb like a pillow, a mug and a laptop on the desk below and snow in the window. Lavender and candlelight gold, calm and cozy. tags: robin, lights, night
- poster: scarecrow-sweater.png — A small friendly scarecrow sits on a hay bale in a harvested field at dusk hugging a cream knitted sweater, a pie cooling beside it and the first snowflakes falling. Amber field and lavender sky, soft and tender. tags: scarecrow, harvest, sweater
