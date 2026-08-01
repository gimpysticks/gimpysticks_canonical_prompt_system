# Change Log

This file records accepted changes to the @gimpysticks prompt system.

Use this file for future updates before folding changes into the modular files.

## 2026-06-30

### Accepted Consolidation Changes

- Consolidated the prompt system into one canonical template baseline.
- Archived the older duplicate template files.
- Made recurring worlds optional instead of mandatory.
- Moved banned or overused worlds and factions into an Archived / Retired section.
- Removed the YAML profile file and replaced it with a Markdown profile library.
- Standardized the primary output format around the user’s most common workflow:
  - MidJourney Prompt
  - Caption / Microstory
  - Hashtags
  - Suggested Audio
- Merged all audio rules into one authoritative section.
- Removed repeated aspect-ratio rules.
- Established the Prompt Priority Hierarchy:
  - Subject
  - Composition
  - Style
  - Atmosphere
  - Lore
- Merged all permanent restrictions into one Permanent Avoid List.
- Separated Permanent Rules from Preference Rules.
- Split the system into modular Markdown files.
- Added this Change Log as a ninth file.

## Active File Structure

```text
Knowledge/
├── 01_Core_Instructions.md
├── 02_Style_Guide.md
├── 03_Output_Format.md
├── 04_Profile_Library.md
├── 05_Character_Library.md
├── 06_Permanent_Avoid_List.md
├── 07_Challenge_Overlay.md
├── 08_Archived_Legacy.md
└── 09_Change_Log.md
```

## Future Change Process

1. Record proposed changes here first.
2. Accept or reject the change.
3. Move accepted changes into the correct modular file.
4. Keep temporary challenge rules in `07_Challenge_Overlay.md`.
5. Move retired concepts into `08_Archived_Legacy.md`.

## 2026-07-02

### Instagram Narrative Optimization

Added a narrative-first optimization pass to improve Instagram engagement while preserving the @gimpysticks Victorian Gothic identity.

Changes include:

- Added Story Moment to the Prompt Priority Hierarchy.
- Added curiosity-first image generation rules.
- Added a generation quality checklist.
- Added narrative style, emotional palette, story scale, viewer curiosity, and visual mystery object guidance.
- Added caption philosophy, preferred caption length, hook structure, and pacing guidance.
- Added social engagement avoid rules to reduce over-explanation, excessive lore, and visually cluttered scenes.
- Preserved profile, character library, challenge overlay, and archived legacy files without content changes.


## 2026-07-02

### Niche Keyword Strategy

Added a separate modular niche strategy file: `10_Niche_Keyword_Strategy.md`.

Accepted niche keywords:

- Victorian Gothic
- Dark Fantasy
- Gothic Horror
- Steampunk Fantasy
- Surreal Fantasy
- Victorian Fantasy
- Dark Art
- Mythic Fantasy
- Cinematic Fantasy
- Visual Storytelling

Defined keyword tiers:

- Primary Brand: Victorian Gothic, Gothic Horror, Dark Fantasy
- Secondary Discovery: Steampunk Fantasy, Victorian Fantasy, Surreal Fantasy
- Supporting Identity: Mythic Fantasy, Dark Art, Cinematic Fantasy, Visual Storytelling

Added guidance for captions, hashtags, alt text, Reel overlays, series titles, and prompt integration.

Core positioning phrase:

`Serialized Victorian Gothic visual stories.`


## 2026-07-27 - Carousel-First Growth Update (Major)

### Problem Identified
- System locked to Reel-first (47/50 last posts as Reels) with static images, causing low watch time negative signal
- 5 hashtag cap from 2023 suppressing discoverability (2026 best practice is 10-12 tiered)
- No Slide 1 hook overlay = low swipe-through, low saves
- High frequency (3-5/day) causing self-cannibalization, avg 11.34 likes at 1.2K followers
- 1:1 following ratio suppressing authority

### Accepted Changes
- **Primary format switched to Carousel (4 slides)** with hook overlay text on Slide 1 and question/CTA on Slide 4
- **Reels now secondary**, only for real motion (zoom, process, parallax)
- **Hashtag rule updated from 5 to 10-12 tiered** (Brand + Discovery + Subject + Mood + gimpysticks)
- **Added Carousel Plan section** to standard output format
- **Added Alt Text section** for Instagram SEO
- **Added Posting Cadence**: max 1/day, 5/week, best times 7-9am / 7-10pm ET
- **Added Audio rule**: only recommend for Reels with motion, prefer trending <10K uses dark ambient
- **Added Following ratio rule**: keep following <800 while growing
- **Added Save CTA requirement** to every caption
- **Challenge Overlay updated** with Reel+Carousel dual strategy
- **New command**: /carousel as primary

### New File Structure
Same 10 files, updated content. Old system archived in 08_Archived_Legacy if needed.

### Core Positioning Unchanged
Serialized Victorian Gothic visual stories.

## 2026-07-27 - Aspect Ratio Removed

### Accepted Change
- Removed the default aspect-ratio rule from the control set.
- Removed the `--ar` parameter from the standard MidJourney output template and examples.
- Future prompts omit aspect-ratio parameters unless the user explicitly requests one.
