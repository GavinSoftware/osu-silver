# osu-silver
## What is osu!silver?
osu!silver is an external all-in-one mod menu created for the rhythm game osu! (only osu!std is supported at the moment), coded completely in C#. This repository is made only for reporting issues and holding data for offsets, the actual program is paid.

The program comes with two modes, Normal and IPC. Normal uses osu!'s memory to modify the game, but is still external. IPC uses osu!'s IPC for Aim Assist and Relax, and does not read/write game memory whatsoever, making it completely external. Each haves their pros and cons. Normal mode allows for more features due to it being able to access memory, but offsets for it will break every update. IPC mode will have less features, but will most likely stay working after an update.

Please note that Normal mode is the only mode made available at the moment, while IPC mode is being worked on.

## Features
### Aim/Tapping
Aim Assist (Normal and IPC) - Helps you aim towards circles/sliders

Relax (Normal and IPC) - Taps the notes for you

### Playback Speed
Timewarp (Normal) - Slows down/Speeds up the game depending on what value you set it on

### Visuals
Approach Rate Changer (Normal) - Changes the AR of a map

Hidden Remover/Flashlight Remover (Normal) - Allows for removal of the flashlight overlay/hidden visual effects

HitObject Locator (Normal and IPC) - Uses windows to show you where the notes are, works fo0r recording if only the osu! window is shown too. (ENABLE BORDERLESS MODE FOR IT TO WORK)

### Replays
Replay Editor (Coming soon, for Normal and IPC) - Allows you to edit how replays look(comes with a cursor and playback speed feature-set, where its almost like external timewarp, xd)
