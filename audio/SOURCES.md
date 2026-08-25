# Sound effect sources

- `generated/ui-tap.wav`, `generated/ui-start.wav`, `generated/answer-correct.wav`, `generated/answer-wrong.wav`, `generated/lesson-complete.wav`: generated locally for this project with Stable Audio 3 Small-SFX. Prompts specify compact Japanese webtoon learning-game UI cues with no voice or copyrighted melody.
- `generated/coach-start.wav`, `generated/coach-cheer.wav`, `generated/coach-success.wav`, `generated/coach-retry.wav`: generated locally for this project with Qwen3-TTS 1.7B VoiceDesign. The voice direction describes an original Korean webtoon learning guide and does not imitate a named real person or character.
- `bgm-three-second-quest-leveled.mp3`: loudness-leveled derivative of the user-provided `bgm-three-second-quest.mp3`, prepared for stable in-app background playback without changing the composition.
- `bgm-three-second-quest-steady.mp3`: dynamically compressed derivative of `bgm-three-second-quest-leveled.mp3`; 20-second loudness windows are held within 0.8 dB to prevent audible level drift during training.
- License: Pixabay Content License, https://pixabay.com/service/license-summary/

Downloaded on 2026-08-25 and bundled for in-app playback. The files are not distributed as standalone media.
