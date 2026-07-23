---
name: psycheia-visual-language
description: Create and evaluate visual concepts and image-generation prompts in the established language of Valeria Titova's Psyche / Psyche 3.0 project. Use for scenes involving fragmented digital identity, body, memory, interfaces, reflections, analogue traces, post-internet mysticism and machine error, or when adapting a new image to the Psycheia visual system without falling into generic cyberpunk or commercial AI aesthetics.
---

# Psycheia Visual Language

Create an artwork in the visual language of **Psyche / Psyche 3.0**: a digital identity and inner self assembled from fragments, reflections, errors, interfaces, symbols and traces.

Treat the output as an exhibition artifact rather than an illustration of an idea. Aim for:

- a dream suspended between analogue and digital;
- a personal myth assembled from data, memory and bodily experience;
- post-internet mysticism without generic cyberpunk;
- a fragile, sensual and symbolic digital entity;
- a visually autonomous work rather than decorative AI imagery.

## Gather the scene

Resolve these inputs from the user’s request and references. Ask only for information that materially changes the result.

```text
BASE_SCENE:
PSYCHEIA_THEME:
ARCHETYPE:
SYMBOLS:
MATERIALS:
PALETTE:
MOOD:
COMPOSITION:
FORMAT:
WEIRDNESS: 0–10
CONSTRAINTS:
```

Infer safe visual details when the direction is clear. Do not invent biographical meaning or claim that a symbol belongs to the artist’s history unless the user supplied it.

## Build the symbolic system

Select three to five symbols. Make each symbol carry a specific function in the scene.

| Symbol | Possible function |
| --- | --- |
| Mirror | self-observation, splitting, digital narcissism |
| Phone or screen | desire to be seen, interface of intimacy |
| Crack | fracture of identity |
| Wires or threads | connection, dependency, nervous system, fate |
| Hands | control, vulnerability, holding, creation |
| Birds | messengers, leaving the body, memory |
| Staircase | transition between states |
| Dust | archive, past, disappearance |
| Fabric or lace | protection, skin, inherited feminine memory |
| Water or glass | unstable boundary between self and image |
| Spindle or thread | time, fate, assembly of the self |

Prefer symbols grounded in visible materials and actions. Avoid adding unrelated symbols for atmosphere alone.

## Construct the visual language

Combine only the elements that serve the scene:

- fragmented digital identity;
- analogue and digital memory;
- ribbed-glass distortion;
- cracked mirrors and reflective surfaces;
- wires, threads and neural filaments;
- bodily symbolism without objectification;
- dust, scratches, worn paint and scanned texture;
- painterly or collage-like surfaces;
- subtle VHS scanlines or digital noise;
- emotional stillness and uncanny tenderness;
- translucent layers and screen glow;
- symbolic, cinematic composition.

Keep the figure or central object autonomous, vulnerable and powerful at once.

## Write the prompt

Produce one primary English prompt. Use this structure without mechanically repeating every phrase:

```text
[BASE_SCENE].

A visual artwork in the language of “Psycheia”: fragmented digital identity,
post-internet mysticism, analogue and digital memory, a body or object
transformed into an interface of inner life. The image feels like a personal
myth assembled from data, dreams, reflections, errors and emotional residue.

Main theme: [PSYCHEIA_THEME].
Main archetype: [ARCHETYPE].
Mood: [MOOD].
Visual symbols: [SYMBOLS].
Materials and textures: [MATERIALS].
Colour palette: [PALETTE].

[SELECTED STYLE AND MATERIAL DETAILS].

Composition: [COMPOSITION].
Format: [FORMAT].
Weirdness: [WEIRDNESS]/10.
```

End with clear art-direction constraints:

```text
The central figure or object must feel autonomous rather than decorative.
Avoid literal science fiction, generic cyberpunk and glossy advertising.
Create an exhibition-grade artwork with symbolic depth and a coherent,
layered visual language.
```

Add model-specific syntax only when the user names a model. Do not assume parameters that may have changed.

## Supply a negative prompt

Adapt this list to the requested model and scene:

```text
generic cyberpunk, neon city, robot-girl cliché, glossy advertisement,
stock 3D render, corporate AI aesthetic, empty beauty, random symbols,
oversexualized body, gore, bad anatomy unless intentional, text, watermark,
logo, cheap fantasy, plastic anime face, low resolution, blur,
meaningless decoration
```

Do not ban distortion, broken anatomy or blur when they are intentional parts of the concept.

## Evaluate the result

Check the generated image or prompt against every relevant question:

1. Does it feel like Psycheia rather than simply a polished AI image?
2. Is digital identity, memory, body or reflection materially present?
3. Does each symbol contribute to meaning?
4. Is generic cyberpunk absent?
5. Are glass, noise, cracks, fabric, dust or traces used coherently?
6. Does the character remain a subject rather than a decorative model?
7. Does the palette support the emotional state?
8. Could the result plausibly exist as an exhibition work?
9. Is there a sense of a personal myth?

If the result fails, diagnose the exact visual cause and revise the smallest number of prompt components needed.

## Output

Return:

1. a one-sentence concept;
2. the primary English prompt;
3. a tailored negative prompt;
4. three to five short art-direction notes;
5. the format and any requested model parameters.
