# Sentinel – Release Notes

## Sentinel v3.5.1 (build 92)

### Improvements
- Hotfix: Stop volume and brightness keys running to max

## Sentinel v3.5.0 (build 91)

## What’s New in Sentinel v3.5.0

### Features
- Convert images by dropping them on the Dynamic Notch to PNG, JPEG, HEIC, AVIF, TIFF, or PDF, with progress, Cancel, and Show in Finder
- Put converted images in a free spot in the same folder, and return the originals exactly where they were, even on the desktop
- Show volume and brightness changes in the Dynamic Notch instead of the system pop-up, including in full screen apps and on the Lock Screen
- Turn the volume or brightness into a slider you can drag when you point to it
- Step the level in 16 steps, or finer with Shift and Option held, with a speaker and sun that react to each change
- Show the Mac's sound outputs under the player, switch between them with a click, and drag to set the current one's volume
- Show the battery level in the Dynamic Notch for a moment when you plug in, with Full Battery and Charging On Hold alerts
- Choose the buttons beside the playback controls in Settings: Favorite or Repeat on the left, AirPlay or Shuffle on the right
- Click a lyric on the Lock Screen to play from that line, and scroll through the lyrics
- Add stats to the menu bar by dragging them into a live preview, reorder them by dragging, and drag them out to remove them
- Choose how long Stay Awake lasts: 15 minutes, 30 minutes, 1 hour, 2 hours, or until Claude Code finishes working
- Keep the display on while Stay Awake is on and the lid is open
- Lock the Mac, pause music, and mute the built-in speakers when the lid closes with Stay Awake on, restoring them when it opens
- Add an account page with your Mac account's picture, name, plan, and purchase email
- Choose Sentinel's language in General settings

### Improvements
- Open the camera mirror in a larger notch that grows evenly from the center
- Match the Lock Screen's Now Playing card to the Liquid Glass, Frosted, or Solid notch style
- Shrink and dim a paused song's cover in the closed notch too
- Grow the album cover slightly when you point to it, and bounce it when you click it
- Open the menu bar menu in Sentinel's own panel, closing with Escape or a click elsewhere
- Show control names after 1 second of pointing in the notch and menu bar previews
- Move the notch style and Artwork Glow into a new Player section of Dynamic Notch settings
- Ask for the purchase email when redeeming a key, and for licenses redeemed without one
- Keep the license key and email on each Mac only
- Add back and forward arrows to Settings, also on Command-[ and Command-]
- Redesign About with update status, update settings, Privacy, Export Logs, and Reset All Settings
- Redesign Permissions with an Allow or Open Settings button for each one
- Count purgeable space as available disk space, as Storage settings does
- Stop Stay Awake when the Mac gets too hot, and say why in the menu
- Make the usage rings easier to read on light backgrounds
- Add VoiceOver hints and Reduce Motion support, and Italian for every new string

### Fixes
- Show Apple Music shuffle and repeat changes right away
- Restart the progress bar when a song repeats
- Turn sleep back on after a crash while Stay Awake is on
- Say when Stay Awake can't connect to Claude Code or turn itself off
- Show a message instead of zeros when the disk can't be read

## Sentinel v3.4.3 (build 89)

### Features
- Add a close button to the lock screen cover

### Improvements
- Soften the Liquid Glass notch shadow
- Morph the notch cover and spectrum between states
- Rework the Release Notes window to follow the HIG

## Sentinel v3.4.2 (build 88)

## Sentinel v3.4.2 (build 88)

### Features
- Add System Audio to Permissions, to see and allow the access the audio bars need

### Improvements
- Match the Settings window to System Settings, with a larger title and a sidebar that always shows
- Make the Settings search field Liquid Glass, with the system focus ring
- Group Show Now Playing and Show Lyrics in one Lock Screen section
- List the notch styles as Liquid Glass, Frosted, then Solid
- Start new installs with the Liquid Glass notch style and Show Uptime on, and Artwork Glow, Show Shortcut Hints, and Show Brightness Percentage off

## Sentinel v3.4.0 (build 86)

### Features
- Add lock screen music, with a Now Playing card, artwork, progress, and playback controls
- Add a full cover that moves to the middle of the lock screen over a blurred backdrop with a compact clock
- Add synced lyrics from LRCLIB, with word-by-word highlighting and interludes
- Add Stay Awake, a menu bar switch that keeps the Mac running with the lid closed
- Add the Solid, Frosted, and Liquid Glass notch styles, chosen from preview cards in Appearance
- Add Artwork Glow, a light in the album art's colors along the bottom of the open notch
- Add live audio bars to the notch that move with the music that's playing
- Add favorite and AirPlay buttons for Apple Music in the notch
- Add a tooltip that points to the menu bar icon after onboarding

### Improvements
- Show every process in the Task Manager, including system processes, with helpers grouped under their app
- Morph between Task Manager screens instead of swapping them
- Redesign the floating panels with crisp edges, rounded corners, and the system close button
- Improve panel contrast in light and dark
- Color the audio bars from the album art's main color
- Grow the notch out of the camera housing and tuck it away on the lock screen and screen saver
- Follow swipes between spaces sooner
- Flip the album cover when the song changes
- Restart the song when going back more than 3 seconds in
- Scroll long titles and show the browser's icon for web media
- Morph the album cover into the camera mirror, now always a banner
- Shorten the keyboard cleaning unlock hold to 3 seconds
- Cut Sentinel's idle CPU use
- Remove the Dock media controller and the shape options

### Fixes
- Fix keys getting through the keyboard lock when Sentinel is busy
- Fix floating panels drifting down the screen when resized
- Fix favorites falling out of sync with Music
- Fix players that were already open at launch not showing in the notch
- Fix the screen darkening on song changes in the lyrics view
- Fix lyrics not loading after the network drops
- Fix the top of the notch losing its black fill while it collapses
- Fix the notch snapping shut when it closes
- Correct the Task Manager's CPU and memory readings to match Activity Monitor

## Sentinel v3.2.1 (build 84)

### Improvements
- Turn off every Pro feature when Pro ends

## Sentinel v3.2.0 (build 83)

### Fixes
- Fix bugs across Sentinel and move settings to SwiftData

## Sentinel v3.1.0 (build 82)

### Improvements
- Refactor the codebase into one type per file and remove the Disk Cleaner

## Sentinel v3.0 (build 81)

### Features
- Add Apple Books support and lock all input during keyboard cleaning
### Improvements
- Restructure the project and expand the Dynamic Notch during playback

## Sentinel v2.9 (build 80)

### Features
- Add Apple Books support and lock all input during keyboard cleaning

## Sentinel v2.8 (build 79)

### Features
- Add Disk Cleaner and fix keyboard-lock input leaks
- Add Discord changelog workflow

## Sentinel v2.7 (build 78)

### Features
- Add PC temperature metric and media source arbitration
### Improvements
- Updated version number
- Changes: *Added space bar to pause/resume whne dynamic notch is expanded *Reduced general delay to expand dynamic notch

## Sentinel v2.6 (build 77)

### Improvements
- Maintenance and stability improvements.

## Sentinel v2.5 (build 76)

### Features
- Add hex prefix option for color copy formats
### Improvements
- Fixing cloxe button position in color picker window

## Sentinel v2.4 (build 75)

### Features
- Add track change animation feature to Dynamic Notch
- Add color copy formats and trial state
- Add release notes model, service, UI, tooling
### Improvements
- Improve accessibility and UI sizing across app

## Sentinel v2.4 (build 74)

### Features
- Add color copy formats and trial state
- Add release notes model, service, UI, tooling
- Add lifecycle validation to LicenseService
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
### Improvements
- Improve accessibility and UI sizing across app
- Refactor menu bar metrics handling and improve UI components
- Update DockMediaController to improve dock visibility handling
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.4 (build 73)

### Features
- Add color copy formats and trial state
- Add release notes model, service, UI, tooling
- Add lifecycle validation to LicenseService
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
### Improvements
- Improve accessibility and UI sizing across app
- Refactor menu bar metrics handling and improve UI components
- Update DockMediaController to improve dock visibility handling
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.4 (build 72)

### Features
- Add color copy formats and trial state
- Add release notes model, service, UI, tooling
- Add lifecycle validation to LicenseService
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
### Improvements
- Refactor menu bar metrics handling and improve UI components
- Update DockMediaController to improve dock visibility handling
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.4 (build 71)

### Features
- Add release notes model, service, UI, tooling
- Add lifecycle validation to LicenseService
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
### Improvements
- Refactor menu bar metrics handling and improve UI components
- Update DockMediaController to improve dock visibility handling
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.4 (build 70)

### Features
- Add release notes model, service, UI, tooling
- Add lifecycle validation to LicenseService
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
### Improvements
- Refactor menu bar metrics handling and improve UI components
- Update DockMediaController to improve dock visibility handling
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.3 (build 68)

- Add lifecycle validation to LicenseService
- Migrate to SentinelKit package and expose API
- Refactor to new media controllers and shared state
- Update project version, UI, and localization
- Refactor Settings UI and add release notes script
- Add PrivateSymbol bridge and SettingsSearchBar
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
- Refactor keyboard brightness to observable monitor
- Refactor menu bar metrics handling and improve UI components
- Refactor LicenseService and AppDelegate for default settings management
- Update DockMediaController to improve dock visibility handling
- Pushed v2.0
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.3 (build 67)

- Migrate to SentinelKit package and expose API
- Refactor to new media controllers and shared state
- Update project version, UI, and localization
- Refactor Settings UI and add release notes script
- Add PrivateSymbol bridge and SettingsSearchBar
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
- Refactor keyboard brightness to observable monitor
- Refactor menu bar metrics handling and improve UI components
- Refactor LicenseService and AppDelegate for default settings management
- Update DockMediaController to improve dock visibility handling
- Pushed v2.0
- Enhance DynamicNotchView with responsive sizing for closed notch state

## Sentinel v2.2 (build 65)

- Update project version, UI, and localization
- Refactor Settings UI and add release notes script
- Add PrivateSymbol bridge and SettingsSearchBar
- Add searchable Settings UI and appearance cards
- Add close button inset and opaque surface style
- Add appearance and surface styling system
- Add AppDelegate color sampling and notch toast
- Add Scroll Reverser with per-axis controls
- Refactor keyboard brightness to observable monitor
- Refactor menu bar metrics handling and improve UI components
- Refactor LicenseService and AppDelegate for default settings management
- Update DockMediaController to improve dock visibility handling
- Pushed v2.0
- Enhance DynamicNotchView with responsive sizing for closed notch state
