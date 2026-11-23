# Ambient background playlist

The landing page can play a small looping playlist of lounge tracks, switched
on by the visitor with the **SOUND / MUTE** pill in the top bar. The tracks
play in order, loop back to the top, and fade gently between songs.

## What to drop here

Three MP3 files, named exactly (the number = play order):

    site/public/audio/track-1.mp3
    site/public/audio/track-2.mp3
    site/public/audio/track-3.mp3

As soon as **track-1.mp3** exists the SOUND pill appears. All three should be
present or the playlist will skip the missing ones.

To change the playlist (more/fewer tracks, different order), edit the `TRACKS`
list in `site/src/useAmbientSound.ts` and drop matching files here.

## Current tracks (chosen 2026-07-13)

Three lounge tracks by **alex-morgan** on Pixabay, used under the
[Pixabay Content License](https://pixabay.com/service/license-summary/)
(free, commercial use, no attribution required):

1. Jazz Rainy Lounge Music — https://pixabay.com/music/modern-jazz-jazz-rainy-lounge-music-556235/
2. Jazz Lounge – Sunny Cafe Music — https://pixabay.com/music/modern-jazz-jazz-lounge-sunny-cafe-music-564270/
3. Piano Lounge – Sunny Cafe Music — https://pixabay.com/music/small-drama-piano-lounge-sunny-cafe-music-564271/

Download each from its page, rename to track-1/2/3.mp3, and place here.

Keep the files reasonably small (MP3, a few MB each) so the page stays light.
Volume is kept intentionally low — see `TARGET_VOLUME` in
`site/src/useAmbientSound.ts`.
