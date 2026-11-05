# Four-deep audio kit

Three music tracks discovered through YouTube and verified against the composer's licensing, plus 100 CC0 interface sound effects downloaded from Kenney's creator upload. All cost $0. Downloaded November 4, 2026. The music MP3s and sound-effect ZIPs are included in this repository.

These are free-to-use licensed assets, not a claim that all music is outside copyright. The three music tracks are CC BY 4.0 and require credit. Kenney's effects are CC0. These third-party audio assets retain their own licenses; the repository's MIT license does not replace them.

## Music

| Track | Best use in Four-deep | File | YouTube preview | License/source |
| --- | --- | --- | --- | --- |
| Sneaky Snitch — Kevin MacLeod | Finesse explaining a hustle; suspicious Doc reactions | [MP3](music/sneaky_snitch.mp3) | [Listen](https://www.youtube.com/watch?v=-SjOkb3kVgI) | [Composer](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1100772), CC BY 4.0 |
| Local Forecast - Elevator — Kevin MacLeod | Awkward silence, waiting for rent, Player's dry reactions | [MP3](music/local_forecast_elevator.mp3) | [Listen](https://www.youtube.com/watch?v=YBAmoSX7isw) | [Composer](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1300012), CC BY 4.0 |
| Monkeys Spinning Monkeys — Kevin MacLeod | Download's tech experiments and light comic chaos | [MP3](music/monkeys_spinning_monkeys.mp3) | [Listen](https://www.youtube.com/watch?v=uXn-zOt68V8) | [Composer](https://incompetech.com/music/royalty-free/index.html?isrc=USUAN1400011), CC BY 4.0 |

Older YouTube descriptions may cite CC BY 3.0. This kit uses MP3s downloaded directly from the composer's current site, whose track pages and license template specify CC BY 4.0. The YouTube links are listening/discovery references, not ripped audio downloads.

## Sound effects

100 original OGG files are bundled in [the original creator ZIP](sources/kenney_interfaceSounds.zip). Original creator pack and license are retained in [sources/](sources/) and [licenses/KENNEY_CC0.txt](licenses/KENNEY_CC0.txt). Ten convenient WAV conversions for common editing apps are in [editor_wav_effects.zip](editor_wav_effects.zip). Extract these ZIPs locally before editing.

- `click_001.ogg`: phone taps and buttons.
- `confirmation_001.ogg`: Download's successful command or a payment notification.
- `error_001.ogg`: declined payment or failed invention.
- `glitch_001.ogg`: a tech malfunction.
- `bong_001.ogg`: a short reaction accent; audition against the scene before using.
- `open_001.ogg`, `close_001.ogg`, `drop_001.ogg`: stylized interface actions/transitions, not recordings of real doors or dropped household objects.
- `glass_001.ogg`, `back_001.ogg`: alternate light accents and interface returns.

Source: [Interface Sounds, uploaded by Kenney](https://opengameart.org/content/interface-sounds). [CC0 terms](https://creativecommons.org/publicdomain/zero/1.0/). Credit is optional: “Interface sound effects by Kenney (kenney.nl), CC0.”

## Add audio to a video

1. Import the finished video, one music MP3 and the chosen WAV/OGG into your editor.
2. Keep the original dialogue track. Put music on a separate track and start about 18–24 dB below the dialogue as an initial mix setting; adjust by ear on a phone speaker.
3. Add one brief effect at the relevant action, below speech level. Avoid a sound effect on every cut.
4. Dip or stop the music just before the punchline, then leave the reaction beat audible.
5. Trim/fade the music to the scene and paste the matching credit from [CREDITS.md](CREDITS.md) into the upload description/caption or visible end credits.
6. Use the [four-video cue sheet](FOUR_VIDEO_CUES.md) and review the whole mix before upload.

## Official YouTube Audio Library alternative

[Open Audio Library](https://www.youtube.com/audiolibrary). In YouTube Studio, choose Audio Library > Sound effects. Suggested search terms: `record scratch`, `door knock`, `phone`, `cash register`, `footsteps`, `crowd`.

Those are search suggestions, not a claim that specific recordings were downloaded or their individual licenses inspected. Download using the library's own button and retain each asset's license information. Standard YouTube Audio Library recordings are not included as raw files in this public repository because this kit has not established permission to redistribute them standalone. For Facebook/Instagram reuse, use the included CC BY/CC0 assets under their documented terms or verify the specific library recording's applicable license.

YouTube documentation: https://support.google.com/youtube/answer/3376882

## Verification

The three MP3s were checked with ffprobe for readable audio streams and duration. The source ZIP was inspected and its 100 OGG files and creator license extracted. WAV conversions were decoded by FFmpeg. This verifies file integrity, not subjective musical fit; the entire tracks have not been auditioned here. Keep [manifest.json](manifest.json) for sources, licenses, hashes and file inventory.
