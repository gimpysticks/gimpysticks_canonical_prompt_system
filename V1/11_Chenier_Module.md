# 11_Chenier_Module

## Command Registration

This file defines one optional style module for the @gimpysticks command-driven prompt system.

Register the following slash commands when this file is loaded:

- `/Chenier` — activate this module.
- `/NoChenier` — deactivate this module.
- `/ChenierOff` — deactivate this module.

## Default State

Inactive.

## Activation Rules

1. Do not apply this module by default.

2. Apply this module only when the user explicitly includes the standalone command `/Chenier`.

3. When `/Chenier` appears in a user prompt, activate the Chenier Module for that response.

4. The module remains active for later responses in the same conversation until the user explicitly deactivates it with `/NoChenier`, `/ChenierOff`, or a direct instruction such as “turn off Chenier.”

5. When deactivated, stop applying all Chenier-specific rendering, coloring, lighting, shading, texture, and keyword guidance.

6. Never activate this module from memory, implication, visual similarity, or prior preference alone. Activation requires `/Chenier` or a direct user instruction.

7. If `/Chenier` conflicts with a higher-priority user instruction, challenge rule, permanent avoid rule, or required output format, follow the higher-priority instruction.

8. If no `/Chenier` command or direct activation instruction is present, ignore the style guidance in this module.

---

# Visual Style Reference Module
**Purpose:** Describe rendering characteristics independently of subject matter. These traits can be mixed into prompts to reproduce the visual language without specifying any particular objects or characters.

---

# Overall Rendering Philosophy

- Hyper-detailed digital illustration with painterly finishing.
- Photorealistic materials blended with stylized proportions.
- Cinematic composition emphasizing atmosphere over realism.
- Every image appears intentionally handcrafted rather than generated.
- Strong emphasis on silhouette readability and visual hierarchy.
- Organic imperfections prevent surfaces from appearing sterile.

---

# Lighting

- Soft volumetric lighting.
- Large diffused key lights.
- Gentle rim lighting separating subjects from background.
- Bloom only on the brightest highlights.
- Minimal clipped whites.
- Ambient occlusion in recesses.
- Deep but readable shadows.
- Subsurface scattering on skin-like materials.
- Atmospheric haze to increase depth.
- Fine edge glow rather than hard outlines.

---

# Color Design

## Overall Palette

- Muted base palette.
- Carefully selected accent colors.
- High color harmony.
- Controlled saturation.
- Cinematic color grading.

## Common Characteristics

- Dusty neutrals
- Smoky blacks
- Warm ivory
- Bone white
- Desaturated teal
- Oxidized copper
- Deep crimson
- Burgundy
- Moss green
- Antique gold
- Charcoal
- Faded lavender
- Cold blue-gray
- Muted emerald

## Accent Strategy

- One dominant accent color.
- One supporting accent.
- Neutral background.
- Localized high saturation instead of global saturation.

---

# Texture Language

## Surface Finish

- Matte rather than glossy.
- Soft velvet diffusion.
- Fine porous detail.
- Organic irregularities.
- Layered weathering.
- Natural edge wear.
- Micro scratches.
- Hairline cracking.
- Fabric weave visibility.
- Slight translucency where appropriate.

## Material Characteristics

Surfaces often resemble combinations of:

- porcelain
- wax
- carved stone
- oxidized metal
- velvet
- silk
- linen
- aged leather
- parchment
- weathered wood
- ceramic glaze
- brushed bronze
- polished bone

---

# Detail Density

- Extremely high micro-detail.
- Small details grouped into larger readable shapes.
- Layered textures.
- Fine edge breakup.
- Controlled visual noise.
- Crisp focal plane with softer peripheral detail.

---

# Contrast

- Medium-to-high local contrast.
- Moderate global contrast.
- Shadows retain information.
- Highlights roll off smoothly.
- Rarely pure black or pure white.

---

# Shading Style

- Painterly gradients.
- Airbrushed transitions.
- Soft reflected light.
- Rounded forms.
- Thick atmospheric depth.
- Limited hard-edge shadows.
- Fine specular highlights.

---

# Background Treatment

- Minimal distractions.
- Heavy depth of field.
- Atmospheric fog.
- Soft gradients.
- Desaturated environments.
- Simplified supporting forms.
- Background values intentionally compressed.

---

# Composition

- Strong central weighting.
- Portrait orientation favored.
- Subjects isolated through lighting.
- Balanced negative space.
- Clear foreground/midground/background separation.
- Diagonal flow lines.
- Asymmetrical balance.

---

# Optical Characteristics

- Shallow depth of field.
- Large soft bokeh.
- Slight lens bloom.
- Fine filmic softness.
- Subtle vignette.
- High dynamic range appearance.
- Delicate chromatic warmth in highlights.
- Cool shadow bias.

---

# Finishing Pass

- Fine color grading.
- Unified tonal curve.
- Gentle atmospheric wash.
- Surface polish without plastic appearance.
- Organic imperfections preserved.
- Rich micro-contrast in focal areas.

---

# Prompt Keywords

hyper-detailed, cinematic lighting, atmospheric depth, volumetric light, painterly realism, muted palette, selective saturation, soft gradients, organic textures, porcelain skin, matte finish, velvet diffusion, layered materials, subtle bloom, high micro-detail, ambient occlusion, shallow depth of field, refined color grading, tactile surfaces, premium digital illustration
