# digitaltrack-video-assets

Public asset repository for the DigitalTrack automated video pipeline.

## Structure

- `music/`
  - `corporate/`: safest default for DigitalTrack explainers and educational shorts
  - `upbeat/`: higher-energy but still broadly usable
  - `tropical/`: warmer lifestyle/promotional feel
  - `indie-rock/`: punchier short-run option
  - `news/`: more newsroom/explainer tone
  - `hiphop/`: selective use only
  - `phonk/`: selective use only
  - `general/`: uncategorized fallback tracks
- `sfx/`: future sound effects
- `licenses/`: source/license evidence and attribution notes

## Recommended default music pool

Start the automated rotation from these files first:

1. `music/corporate/chasing_success_joyinsound.mp3`
2. `music/corporate/corporate_prettyjohn1.mp3`
3. `music/upbeat/upbeat_background_the_mountain.mp3`
4. `music/upbeat/energetic_atlasaudio.mp3`
5. `music/tropical/golden_waves_pink_sound.mp3`
6. `music/indie-rock/motivating_indie_rock_30s_universfield.mp3`
7. `music/general/background_monume.mp3`

These are the closest fit for:

- local business marketing explainers
- Spanish voiceover with English text overlays
- low-volume background bed under narration

## Licensing note

This repo currently stores downloaded source files plus organizational metadata.
Before using any track in production, add source/license proof under `licenses/`
and confirm whether attribution is required.

## Pipeline note

The video pipeline should read:

- `music/catalog.json` for labels and metadata
- `music/default_rotation.json` for preferred rotation order
