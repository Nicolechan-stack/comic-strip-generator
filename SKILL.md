# 哲理四格漫画创作 — Skill Prompt

> YouMind Skill: https://youmind.com/skills/RiAnaPXAmCmR5l

---

## Step 1: Understand the Theme

First, carefully understand the topic concepts provided by the user. Confirm:

1. What is the core meaning of the theme?
2. Is it a philosophical piece about life or a satirical piece about the industry?
3. Are there any requirements regarding the protagonist's gender/characteristics?
4. Does it involve real people or brand logos?

If the topic is unclear, ask the user for clarification.

## Step 2: Create the Story

Based on the theme, create a philosophical four-panel comic strip story. Story structure:

**First Section: Presentation of the Problem/Current Situation**
- Scene Description
- Character actions and expressions
- Dialogue content
- Narration (stating the theme)

**Second Section: Problem Escalates/Conflict**
- Scene Description
- Changes in character movements and expressions
- Dialogue content
- Narration (revealing the predicament)

**Third Section: Turning Point/Awakening**
- Scene Description
- Character movements and facial expressions
- Dialogue content
- Narration (to guide thought)

**Fourth Section: Sublimation/Wisdom**
- Scene Description
- The character's movements and expressions are relaxed.
- Dialogue content
- Narration (conveying philosophical ideas)
- Orange label (core keywords)

**Story Highlights:**
- Use visual metaphors (e.g., pushing against a wall and a door, gripping and releasing, height and flowers, etc.).
- Strong contrast (first three panels vs. fourth panel)
- The ending elevates the theme and conveys profound philosophical insights.
- Concise and powerful, without being verbose

Present the complete four-panel story to the user for confirmation.

## Step 3: Generate the Illustration

Use the imageGenerate tool to generate the illustration. Strictly follow the prompt template below:

```
Four-panel comic strip, 2x2 grid layout (two rows and two columns), minimalist line art style, business illustration style. Pure white background, outlined with black lines, orange is used only as the accent color for key labels, and the use of orange is very restrained. Except for a very small amount of light brown used for wooden objects, gray tones are not used.

At the top of the entire four-panel comic strip, the title is written in clear black Chinese font: "[Topic Name]".

Character Style: Simplified yet proportionally balanced character design (not stick figure): round head, minimalist facial features (two dots for eyes, an arc for mouth, simple hairstyle outline), and clearly defined details on the body, including shirt collar, sleeves, pants, and shoes. The character occupies a relatively small proportion of the image (mid-to-long distance). Characters are distinguished by different hairstyles: bald, short hair, medium-length hair, etc.

Four-grid layout: a grid layout with 2 rows and 2 columns of squares. The border of each square is hand-drawn with slightly natural curves (not completely straight).

Key stylistic features: clean lines, simplified figures with individuality, figures in appropriate proportions, pure white background with only black outlines, orange used only for key labels and very restrained, minimal shadows (light brown is used only for wooden objects), slightly irregular borders with a hand-drawn aesthetic, and clear outlines of business casual clothing.

[If brand logos are involved, add:] Important: Each person's logo should be displayed on their chest (simplified version, outlined in black, Claude logo filled with a warm rust orange).

First panel (top left): [Detailed description of the scene, characters, actions, expressions, dialogue, and narration]
Second panel (top right): [Detailed description of the scene, characters, actions, expressions, dialogue, and narration]
Third panel (bottom left): [Detailed description of the scene, characters, actions, expressions, dialogue, and narration]
Fourth panel (bottom right): [Detailed description of the scene, characters, actions, expressions, dialogue, and narration, emphasizing that the orange label is the only orange element in the entire painting]
```

**Key Parameters:**
- model: `gemini-3.1-flash-image-preview`
- aspect_ratio: `16:9`
- quality: `medium`
- title: `[Theme Name] - Four-Panel Comic`

**Important Notice:**
1. The prompts must be very detailed, including the scene, characters, actions, expressions, dialogue bubbles, and bottom descriptions for each cell.
2. Orange is used only for the key tag in the fourth cell; extreme restraint is required.
3. If real people are involved (such as Sam Altman, Dario Amodei, Elon Musk), their actual physical characteristics need to be described.
4. If brand logos are involved (such as ChatGPT, Claude, Gemini, Grok), the logo characteristics need to be accurately described.
5. Claude logo characteristics: square or rounded square, warm rust orange (#C15F3C), with abstract geometric patterns inside.

## Step 4: Review and Iterate

After generation:

1. **Display Results** — The four-panel comic has been automatically displayed.
2. **Inquire about user feedback:**
   - Are you satisfied with the storyline?
   - Do the characters/roles need to be adjusted?
   - Does the visual style need to be changed?
3. **Optimization options are provided:**
   - Modify the storyline
   - Adjust character traits (gender, hairstyle, clothing)
   - Modify the scene or dialogue in a specific cell
   - Adjust the viewing angle (e.g., switch to a top-down view)
   - Regenerate
4. **Provide prompt words:**
   - If users want prompts to use for their own optimization, provide a complete prompt generation tool.
5. **Next step suggestion:**
   - Continue creating other themes
   - Save your work to board
   - Publish and share
