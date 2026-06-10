# Awakening bridge audio

Put one legally licensed or self-provided invocation file here with one of these names:

- `persona-invocation.mp3`
- `persona-invocation.ogg`
- `persona-invocation.wav`

The awakening bridge checks these files in that order. If no file is present, it falls back to the built-in generated audio layer:

- low rumble under the rumor collapse
- whisper-like noise during the black-screen pause
- generated invocation tones when no licensed voice file is present
- blue-butterfly chimes and release flutter

Current bundled replacement assets:

- `awakening-reveal.ogg` - magical reveal accent from OpenGameArt's "Magic Spell SFX" page: https://opengameart.org/content/magic-spell-sfx
- `awakening-whisper.mp3` - whisper/noise bed from BigSoundBank's "Whisper 2" page: https://bigsoundbank.com/whisper-2-s3256.html
- `phone-message-ringtone.mp3` - user-provided phone notification ringtone for the opening phone scene.

Optional scene accent slots:

- `awakening-reveal.mp3/.ogg/.wav` - plays when the invocation line appears.
- `awakening-whisper.mp3/.ogg/.wav` - loops quietly while the voices collapse.
- `awakening-butterfly.wav/.ogg/.mp3` - plays when the blue butterfly settles. If absent, the bridge uses generated chimes.

Do not commit ripped game audio or copyrighted dialogue here unless you have explicit permission to use it in this project.
