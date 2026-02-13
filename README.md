# BlackBox Cue

A simple and powerful audio cue player for theater, live shows, and stage events. Also ideal for any place that needs background music: waiting rooms, shops, restaurants, exhibitions, and more.

![BlackBox Cue](screenshot.png)

---

## Why BlackBox Cue?

BlackBox Cue is designed for **live, reactive use**. Unlike traditional cue list software that requires extensive pre-programming, BlackBox Cue works like a **sound palette**: all your audio files are laid out on pads, ready to be triggered instantly with a single click.

This makes it the ideal tool for:

- **Theater rehearsals** where the director tries different sounds on the fly and timing changes constantly
- **Improvisation shows** where nothing is scripted and the sound operator reacts in real time
- **Dance rehearsals** where music needs to be started, stopped, and switched quickly
- **Young audience shows** where timing depends on the audience's reactions
- **Any live situation** where you need to adapt on the spot rather than follow a fixed sequence

No complex setup, no programming, no learning curve. Import your files, and you're ready to go.

---

## Getting Started

### Installation

1. Download the latest release
2. Run the installer
3. Launch BlackBox Cue

### Requirements

- Windows 10 or 11 (64-bit)
- An audio output device 

---

## Your First Project

### Create a New Project

1. Click the **New** button
2. Choose a folder where your project will be saved
3. A `.bbcue` project file and an `imports` folder are created automatically

The `imports` folder is where all your audio files will be stored.

**Note:** You must create a new project or open an existing one before you can start working with pads.

### Open an Existing Project

Click the **Open Project** button and select a `.bbcue` file.

---

## Importing Audio Files

BlackBox Cue supports **WAV**, **MP3** and **AIFF** audio files.

AIFF files are automatically converted to WAV format during import.

### Import a Single File

1. Click the **Import** button
2. Select an audio file from your computer
3. Give it a name (or keep the original)
4. For WAV and MP3 files, the file is copied into your project's `imports` folder. The copy is secured: the integrity of the destination file is verified against the source file to ensure no data was lost or corrupted
5. For AIFF files, the file is converted to WAV format and saved into your project's `imports` folder. 

### Auto-Assign (Bulk Import)

To quickly fill all pads at once:

1. Click on "Switch to crossfade mode"
2. Click the **Auto-Assign** button
3. Select a folder containing your audio files (subfolders are included)
4. Confirm the operation (this will erase all existing pads)
5. Files are automatically copied, assigned to pads, and named

This is useful for quickly setting up a show with many sound cues.

---

## Pads

BlackBox Cue gives you **108 pads** organized across **9 pages** of 12 pads each.

Each pad can hold one audio file and has its own playback settings.

### Playing a Pad

Simply click a pad to play it. The pad lights up green while playing.

### Navigating Pages

- Use the **Page Up** and **Page Down** buttons to switch between pages
- The current page number is shown at the top of the screen

---

## Edit Mode

To configure a pad, switch to **Edit Mode** by clicking the **Edit** button.

In Edit Mode, clicking a pad selects it for editing (it lights up yellow). You can then:

- **Assign an audio file** using the Browse button
- **Set a caption** (the name shown on the pad, up to 14 characters)
- **Choose an end behavior** (what happens when the track finishes)
- **Choose a start behavior** (where playback begins)
- **Save** 

### End Behavior

- **One-Shot** : the track plays once and stops
- **Loop** : the track repeats indefinitely (ideal for ambient sounds or music loops)
- **Continue** : when the track ends, the next pad plays automatically (ideal for sequential cue lists)

### Start Behavior

- **Start from zero** : playback begins at the very start of the file
- **Auto-Trim** : playback skips any silence at the beginning and at the end of the file (detected automatically). Note: Auto-Trim only works if the silence does not exceed 10 seconds. Beyond 10 seconds, the silence is considered intentional and part of the track, so it will be played normally
- **Custom offset** : playback starts at a time you choose, adjustable with the +/- buttons

### Waveform Display

In Edit Mode, a waveform of the audio file is displayed. Click the waveform to toggle between viewing the **beginning** and the **end** of the track.

An yellow line indicates the Auto-Trim start point. An orange line indicates the Auto-Trim end point. A cyan line shows your custom start offset.

---

## Playback Controls

### Stop

Click the **Stop** button to stop playback.

- If a fade-out is configured, the first press starts the fade-out
- Press again during the fade to stop immediately

### Pause / Resume

Click the **Pause** button to pause playback. Click it again to resume. The time display blinks while paused.

### Seek

Click on the progress bar to jump to any position in the track.

---

## Fade Controls

### Fade-In

Set the duration of a smooth volume ramp-up when a track starts playing. Adjustable from 0 to 10 seconds.

- Click **+** or **-** to adjust by 0.2 seconds
- Hold **Shift** and click to adjust by 1 second
- Hold the button to auto-repeat

### Fade-Out

Set the duration of a smooth volume ramp-down when you press Stop. Adjustable from 0 to 10 seconds. Same controls as Fade-In.

### Crossfade

Enable the **Crossfade** checkbox to smoothly transition between tracks. When you play a new pad while another is playing, the old track fades out while the new one fades in simultaneously. The crossfade duration is adjustable from 1 to 10 seconds.

---

## Volume

Use the vertical **volume fader** on the right side of the screen to adjust the output volume. Drag it up to increase volume, down to decrease.

### Volume Normalization

Enable the **Normalize** checkbox to automatically balance the volume across all your tracks. Audio files are often recorded at different levels, which can cause jarring volume jumps when switching between pads.

When normalization is enabled, BlackBox Cue analyzes the RMS level of each audio file and adjusts the playback gain so that all tracks are perceived at a consistent volume. 

---

## VU Meter

The LED-style VU meter shows the real-time audio output level, with a peak indicator.

---

## Display

During playback, the screen shows:

- **Track name** : the filename of the current audio
- **Elapsed time** : how long the track has been playing
- **Remaining time** : how much time is left
- **Playback mode** : LOOP, ONE-SHOT, or CONTINUE

---

## Wireless Presenter Support

BlackBox Cue is compatible with wireless presenters (the kind used for PowerPoint presentations).

Enable the **Remote** checkbox, then use your presenter to control playback hands-free:

| Button | Action |
|--------|--------|
| Volume Down | Play the selected pad |
| Volume Up (short press) | Stop playback |
| Volume Up (long press >2s) | Advance to the next pad |
| Page Down | Select next pad |
| Page Up | Select previous pad |
| B key | Stop playback and advance to the next pad |

The selected pad is highlighted on screen. Navigation automatically switches pages when needed (in both directions).

---

## Tips

- **Sleep prevention** : BlackBox Cue automatically prevents your computer from going to sleep or turning off the screen while the application is running, so your show won't be interrupted.
- **Continue mode** : Use Continue mode across all your pads to create an automatic playlist that plays through your entire cue list.
- **Crossfade + Continue** : Combine crossfade with Continue mode for seamless transitions between tracks.
- **Auto-Trim** : Most audio files have a small amount of silence at the beginning. Auto-Trim detects this and skips it, so your cues start right on the sound. Silence longer than 10 seconds is considered intentional and will not be trimmed.

---

## License

Copyright (c) 2025 Cyril LAMY. All rights reserved.

This software is **FREEWARE**. You may use and distribute it freely for personal or commercial purposes.

**DISCLAIMER:** This software is provided "as is", without warranty of any kind. The author shall not be liable for any claim, damages, or other liability arising from the use of this software.

---

