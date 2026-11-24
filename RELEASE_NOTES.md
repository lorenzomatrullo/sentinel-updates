# Sentinel – Release Notes

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
