# Synced LRC Lyrics

A collection of manually synced `.lrc` lyric files for songs that are missing synced lyrics or have inaccurate timing.

The main goal of this repository is simple: keep the lyrics lined up with the audio as closely as possible.

## What is included

Files may include:

- Original-language lyrics
- English translations
- Synced `.lrc` files
- Alternate versions or remixes

## Timing

Most songs are timed manually.

For songs that are harder to sync, I usually make multiple timing passes and compare them before making a final version.

The general process is:

1. Listen to the song
2. Mark the beginning of each lyric line
3. Repeat the timing process a few times
4. Compare the results
5. Fix missed or incorrect timestamps
6. Test the finished file in a music player
7. Adjust anything that still feels early or late

A normal LRC file looks like this:

```lrc
[ar:Artist Name]
[ti:Song Name]

[00:20.81]First lyric line
[00:24.34]Second lyric line
[00:27.04]Third lyric line
```

The timestamp marks when the lyric line should appear.

## Current songs

### The Larping Tombstone - Looping the Rooms

Includes:

- Original Japanese lyrics
- English translation
- Synced remix version

This song was synced using several manual timing passes and then tested in an actual music player.

## Translations

Some songs may include English translations.

Translations are intended to keep the original meaning readable in English and may not always be completely literal.

## Repository layout

```text
lyrics/
└── artist-name/
    └── song-name/
        ├── original.lrc
        ├── english.lrc
        └── README.md
```

## Reporting bad timings

If a timestamp is wrong, include:

- Song name
- Lyric line
- Current timestamp
- Suggested timestamp
- Audio source or version

Example:

```text
Song: Example Song
Line: Example lyric
Current: 01:24.32
Suggested: 01:24.17
Source: YouTube
```

## Copyright

Lyrics and music belong to their respective artists, songwriters, publishers, and copyright holders.

This repository only contains timing data, lyric files, and translations for use with music players.

No ownership of the original music or lyrics is claimed.
