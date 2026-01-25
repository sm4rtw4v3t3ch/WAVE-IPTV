```markdown
# WAVE IPTV
# TV User Guide (English)

**Document version:** 1.0 | **Date:** December 18, 2025

> ℹ️ **INFO: About this guide**  
> This guide is based on the WAVE IPTV Application and is intended for end users on Android TV & Fire TV compatible Devices.  
> Premium features are marked with *** throughout the guide.

---

## Table of contents

1. Overview  
2. Requirements and key concepts  
3. First launch and onboarding flow  
4. Importing a playlist  
5. Navigation basics (Android TV focus)  
6. Movies and Series screen  
7. Details screen (Movie / Series)  
8. Favorites and History (VOD)***  
9. Search (text and voice)  
10. EPG screen (TV guide and TV groups)  
11. Custom Groups (Movies / Series / Channels)***  
12. VOD Video Player (Movies and Series)  
13. TV Player (Live)  
14. Profiles and Playlists  
15. Settings (Preferences and management)  
16. Premium edition: what you get (*** features) and free trial  
17. Troubleshooting  
18. Glossary  

---

## 1. Overview

WAVE IPTV is an Android TV application that lets you watch:

- Live TV channels (with EPG TV guide, channel groups, favorites, and history)
- Movies (VOD)
- Series (VOD, with seasons and episodes)
- Unified search across movies, series, channels, and EPG programs

The app is organized around the following screens:

- Intro screen
- Playlist import screen
- Movies and Series
- Movie/Series details
- EPG (TV guide and TV groups)
- Search
- VOD video player
- TV player (Live)
- Settings
- Profiles and Playlists

Disclaimer : This app DOES NOT PROVIDE ANY CONTENT , you need to import your own playlists!!!

---

## 2. Requirements and key concepts

### 2.1 Supported playlist types

You can connect WAVE IPTV using access details provided by your IPTV provider, typically in one of these formats:

- M3U link (a direct URL to a .m3u/.m3u8 file, or a redirect link)
- Xtream Codes (always 3 fields: server URL, username, and password)
- Some providers share an M3U link that is Xtream-style. WAVE IPTV also accepts it in the M3U import method. (example : http://server.com:port/get.php?username=XXX&password=XXX&format=M3U&output=ts/hls)

### 2.2 The Android TV "focus" model

On Android TV, you navigate using the focus (the selected item outline) with the D-pad arrows on your remote.  
In this app, many actions change depending on the gesture, but these two actions are often the same by default:

- Short press: select or open
- Long press: open a contextual menu

N.B: you can map the buttons of your remote (premium version) when you need it. See “Remote mapping” section below (15.10)

---

## 3. First launch and onboarding flow

### 3.1 Intro screen

On the very first launch, WAVE IPTV shows a short intro screen that explains what the app does.  
This intro is shown only once.

### 3.2 Playlist import screen

After the intro, you land on the playlist import screen. This is where you connect your provider’s playlist or restore a backup.

---

## 4. Importing a playlist

WAVE IPTV offers five import methods (one is planned for a future release).

### 4.1 Restore a backup

Goal: reload a backup that was previously created inside the application.  
Result: the entire app state is restored, including:

- Preferences
- Imported content
- Ordering and organization
- Any other saved state at the time of backup

You can also find backup/restore later under Settings > Preferences > Backup and restore.

Steps:

- From the import screen, choose Restore a backup
- Select the backup file
- Confirm
- Wait for the restore to complete
- Once finished, the app returns to the exact state of the backup

### 4.2 Import via QR code scan (web flow)

Goal: avoid typing with the remote. You scan a QR code and enter your details on your phone or tablet. The TV receives the playlist automatically.

How it works:

- On the TV, choose Import via QR code
- Scan the QR code using your phone or tablet
- You are redirected to the WAVE IPTV website
- The website offers two tabs: M3U URL and Xtream Codes
- Fill in the fields depending on your choice:
- M3U URL: paste the URL, then validate
- Xtream Codes: enter server URL, username, and password, then validate
- Validate. The playlist is sent to the TV app

> 💡 TIP: Expected transfer time  
> Transfer to the TV is usually immediate (about 1 to 2 seconds).

> ⚠️ WARNING: If nothing happens after 30 seconds  
> Close the app on your TV, reopen it, and try again. The server may be temporarily busy.

### 4.3 Import via M3U link (inside the app)

Goal: import by typing or pasting an M3U URL directly in the app using your remote.

Accepted inputs:

- Direct link to an M3U file
- Redirect link
- Xtream-style M3U links provided by some IPTV providers

Steps:

- On the import screen, choose M3U link
- Enter or paste the URL
- Validate
- Wait for content insertion

### 4.4 Import via Xtream Codes (inside the app)

Goal: import by entering three fields using your remote.

Required fields:

- Server address (URL)
- Username
- Password

Steps:

- On the import screen, choose Xtream Codes
- Fill in the three fields
- Validate
- Wait for content insertion

### 4.5 Cloud Sync (coming January 2026)

Cloud Sync is planned for January 2026. It is not available yet. This guide will be updated when the feature is released.

### 4.6 Common import mistakes (very important)

These are the most frequent causes of import failures:

- HTTP changed to HTTPS: some phones/tablets auto-rewrite http to https when you copy-paste a url. If your provider requires http, remove the extra 's'.
- Leading or trailing spaces: ensure there are no spaces before or after the URL.
- QR transfer too slow: normally 1 to 2 seconds. If nothing after 30 seconds, close and reopen the TV app and retry.

### 4.7 Insertion time and automatic redirection

After validation, you will see an insertion progress indicator (number of items being loaded).

Typical insertion time:

- Often 1 to 2 minutes
- Sometimes faster or slightly longer depending on playlist size

When import finishes, WAVE IPTV redirects automatically:

- If the playlist contains only TV channels: you are redirected to the TV screen
- If the playlist contains also movies and series: you are redirected first to ”Movies and Series” screen

---

## 5. Navigation basics (Android TV focus)

On the two main screens (TV or Films & Series), a vertical menu bar appears on the left:

- It is collapsed by default (only icons are shown)
- It expands when you move focus onto it (icon plus label)

---

## 6. Movies and Series screen

### 6.1 Menu sections

In the left menu, you will find these sections:

- Profile
- TV
- Movies
- Series
- Favorites
- History
- Settings

At the top of the screen, you also have shortcuts:

- Search (magnifier icon): opens the Search screen
- Filter/Sort (top-right): filter content and change ordering

### 6.2 Movie/Series groups (categories) and drawer

From the Movies and Series screen:

- Selecting Movies shows the list of movie groups
- Selecting Series shows the list of series groups
- Selecting TV switches to the TV/EPG experience

In the group drawer (Movies and Series), two shortcuts are available at the top:

- Active playlist: shows the current playlist name and opens playlist management to switch or add playlists.
- Custom groups: opens the Custom Groups manager.

### 6.3 Layout: preview area plus poster grid

The screen is organized into two key areas:

- Top area (focused item info): poster, title, and metadata such as rating, director, cast, description, runtime, and release date (when available).
- Bottom area (poster grid): a grid with 6 posters per row. Use the remote arrows to move through rows and columns.

### 6.4 Short press vs long press (context menu)

- Short press on an item: opens the Details screen (movie or series).
- Long press on an item: opens a context menu that can include:
- Add to favorites / remove from favorites
- Open details
- Add to a custom group
- Remove from history (if already watched)
- Start playback immediately (without opening details)

---

## 7. Details screen (Movie / Series)

### 7.1 Main information and buttons

The details screen shows the full synopsis and metadata, and includes three main actions:

- Watch / Resume / Start
- Trailer
- Add to favorites

### 7.2 Play using an external player (VLC, etc.)

On the Watch button:

- Long press opens a context menu with an option to play in an external player
- This is available only if you have an external player installed on your device (for example VLC)

### 7.3 Series specifics: seasons and episodes

Below the main buttons the following elements are shown:

- Season tabs (Season 1, Season 2, etc.)
- A horizontal episode list for the selected season (navigate with focus)

Click on the season tab to show the episodes of the season in the list  
Episodes may display a name when available.

> ℹ️ INFO: Metadata note  
> Films, Series and episode metadata often comes from The Movie Database (TMDB), so it can differ from the information shown in the Movies and Series grid (which follow your provider's data). The most recent info are always show in the details screen (like ratings for example)

Episode progress  
If an episode has saved progress, a small blue progress bar is shown under that episode.  
Selecting the episode resumes from the saved position. You can restart an episode at any time from the video player using the Restart button in the controls panel.

---

## 8. Favorites and History (VOD)***

> ℹ️ INFO: Premium feature  
> This section is a Premium feature. Premium features are marked with ***.

### 8.1 Favorites***

The Favorites section shows all favorited items, mixing movies and series.  
The filter icon in the top-right lets you display:

- Movies only
- Series only
- Movies and series

Add to favorites : just long click on a content to add it as favorite or click on the button “add to favorites” when in the details screen.

Removing favorites:

- Long press on an item then choose remove from favorites
- Use the trash icon above the grid to remove all favorites

### 8.2 History***

History contains content you have watched.  
By default, a movie is added to history after 1 minute of playback (this is configurable in preferences).

Removing history:

- Long press on an item then choose remove from history
- Use the trash icon to clear the entire history

---

## 9. Search (text and voice)

### 9.1 Text search

When you open the Search screen, the search field and keyboard open automatically.  
Results are dynamically shown in the search when you are typing the keyword (needs at least 3 letters typed)

### 9.2 Voice search

To use voice search:

- Close the on-screen keyboard (Back press)
- Select the microphone icon next to the magnifier icon

Voice search uses the language configured in the app.  
This requires a voice-capable remote control and to allow permission for audio recognition.

### 9.3 Search tabs

You can filter your keyword search by content type:

- All (default)
- Movies
- Series
- TV Channels
- Programs

Filter on a specific section can accelerate the search.  
You can set the default tab under Settings > Preferences.

### 9.4 Title / description filter

A filter lets you search:

- Title only (default)
- Description only
- Title and description (can slow the search)

### 9.5 Results and actions

Results are displayed as a grid.

- Long press on a result: add to favorites or remove from favorites. Visual cue: a yellow star on the card means it is already marked as a favorite.
- Short press on a result: open the related page:
- Movie/Series: opens the Details screen
- Channel/Program: opens the TV player with the live channel or program in progress

> ⚠️ WARNING: Programs may not be playable  
> A program can be in the past or in the future. If replay is not available, past programs cannot be relaunched and a pop-up will inform you. If the program is currently running, you will be redirected to the channel itself.

---

## 10. EPG screen (TV guide and TV groups)

### 10.1 Side menu

On the EPG screen, the left menu is available but does not include the History section (TV history is mainly handled inside the TV player).

### 10.2 Display modes

Two EPG display modes exist:

- List mode
- Grid mode

Use the icon above the TV guide to switch between modes.

### 10.2b Filters

Two other filters exist:

- Filter by day to switch to another date
- Filter by time of day to easily switch to morning/afternoon/evening period

### 10.2b Back to live & Fullscreen buttons

Finally Two other buttons can appear sometimes in the list mode:

- Back to live : appears when on another day or when the current program is no more visible. Makes you go back to the current program with a scroll animation
- Fullscreen : Appears when the stream is in preview mode and lets you go fullscreen. Another way to go fullscreen is to click twice on the program, or to long press on the “back” button of your remote

### 10.3 TV groups (drawer menu)

A drawer menu lists the TV groups.

Behavior:

- Moving focus onto a group loads automatically its content, you don’t need to click on the group
- Selecting a group will close the drawer and moves the focus to the first in-progress program of the first channel. The same behavior happens if you press Right on your remote from the group list.

### 10.4 Replay and the clock icon

In list mode, if a channel supports replay, a small clock icon appears in the channel column:

- Clock present: replay is available
- No clock: replay is not available

### 10.5 Long press on a program (context menu)

Long pressing a program opens a contextual menu that can include:

- Program details (full synopsis, date, start time, end time, etc.)
- Add channel to favorites or remove it from favorites
- Add to a custom group
- Schedule a reminder
- Open with (lets you play the stream in an external player like for VOD)

### 10.6 Shortcuts at the top of the group drawer

At the top of the group drawer, two icons provide quick access:

- Active playlist: on focus, shows the active playlist name. On select, opens playlist management to switch or add a playlist.
- Custom groups: opens the screen to create and manage custom groups.

---

## 11. Custom Groups (advanced feature)***

> ℹ️ INFO: Premium feature  
> Custom Groups are a Premium feature (***).

You can create your own groups with a name, optional color (depending on content type), and custom content selection.

### 11.1 Most important rule

A custom group can contain only one content type:

- Movies only, or series only, or TV channels only
- No mixing across types

### 11.2 Create a custom group

- Open the Custom Groups screen
- Select Create a new group
- Name the group
- Choose the content type (movies, series, or channels)
- Use the search field to find content
- In the grid, select an item to add or remove it from the group
- Use the filter icon next to the search field to show only items already added

### 11.3 Edit a custom group

Depending on the screen, top-right actions can include:

- Rename
- Change color
- Delete

### 11.4 Add items quickly via context menus

After creation, your custom group appears in context menus:

- Long press on a movie/series in Movies and Series
- Long press on a channel program in the EPG

This lets you add content on the fly without returning to the Custom Groups manager.

---

## 12. VOD Video Player (Movies and Series)

### 12.1 Show playback controls

During playback, press OK (center button) to show the control panel (play/pause, seek forward/back, etc.).

### 12.2 Bottom icons: audio, subtitles, settings, restart

The player provides icons that open additional actions:

- Select audio track (if available)
- Subtitles: enable/disable, change subtitle appearance, enable OpenSubtitles***
- Advanced settings (technical details, audio/video options)

### 12.3 Key advanced options

Depending on your device and setup, you can:

- Enable auto resolution (fit content to your display)
- Enable auto frame rate (match TV refresh rate to the content frame rate)
- Enable audio passthrough (useful with an AV receiver)
- Adjust audio delay (positive or negative) to correct lip-sync issues
- Show technical details

### 12.4 Left/right side panels (when controls are hidden)***

When the control panel is not visible:

- Press Left to show content details (synopsis, poster, rating, etc.)
- Press Right to show a vertical list of items from the same group
- For series: this list shows episodes for the current season
- You can navigate and start another episode or item directly

### 12.5 Series specific options

In the control panel (series), additional buttons may appear at bottom-right:

- Previous/next episode
- Auto-play next episode (enable/disable)

### 12.6 Technical diagnostics (QR)

In the advanced settings option, a detailed technical diagnostic can be displayed (audio, video, stream information).  
You can scan a QR code to send the report by email if needed.

---

## 13. TV Player (Live)

### 13.1 Preview vs full screen

From the EPG:

- First click on a program: plays it in a preview window
- Second click on the same program, or a long Back press from the EPG: switches to full screen

### 13.2 Control panel (OK)

In full screen:

- Short Press “OK” on your remote to display the control panel
- Similar options to the VOD player are shown: audio sync, advanced settings, etc.
- You can also easily switch quality for the same channel if available (for example FHD to HD to SD)
- Live return button (this icon is shown only if the stream was paused)
- EPG button: opens the integrated detailed EPG panel inside the player. Similar to long press on “OK” button when the controls panel is hidden (see below).

### 13.3 Side panels (when controls are hidden)***

When the control panel is not visible:

- Press Left: show details of the current program. Back or right to close this panel when open.
- Press Right: show the channel schedule list for the current day:
1.Focus starts on the current program
2.Up/Down: move through programs
3.Left/Right: change day
4.Back: closes the open panel
5. click on a program to start the replay (if available)

### 13.4 Advanced zapping view (double press or long press OK)***

Double press OK quickly, or long press OK, to open an advanced view that shows:

- Group list
- Channel list
- Program list for the active channel

This allows fast switching of channels or groups without returning to the EPG screen.  
A Favorites group is available in this view (first group, only if you already have added a favorite), containing your favorite channels.

### 13.5 TV Favorites and TV History panels***

When the control panel is visible:

- Favorites button: opens a horizontal panel of favorite channels (with the current program for each)
- From the control panel, press Down: opens TV History (same layout as favorites)

A channel is added to TV history by default after 1 minute of playback. This is configurable in preferences.  
To remove one content from the favorites/history : long press on the content.  
To add a channel to favorites : yellow color button on your remote (you can also define a specific button in the remote mapping section  see 15.10)

### 13.6 Channel up/down zapping (when controls are hidden)

When controls are hidden:

- Up/Down switches to the previous or next channel in the group

### 13.7 Long-press directional actions***

When the control panel is not visible, long pressing Left/Right/Up/Down can trigger extra actions, depending on your configuration. Examples include:

- Return to the previously watched channel
- Open Search directly
- Show History
- Show Favorites
- Open advanced settings

These actions are configurable under Settings > Remote mapping (see 15.10).

### 13.8 Advanced TV player settings (key points)

In advanced settings, you may find some options:

- Auto frame rate
- Audio passthrough
- Audio tunneling (not recommended by default, but helpful in some cases)
- Software audio decoding (can help certain channels). Note that if audio passthrough is enabled, software decoding is disabled automatically
- Subtitles (if available)
- Auto resolution limited to screen (format adaptation)
- Technical diagnostics (with QR code)
- …

### 13.9 Safe transition option (preview <-> full screen)

A specific option can fully stop the stream for 1 to 2 seconds when switching between preview and full screen.  
It is not recommended for most devices, because you temporarily lose audio and video.  
However, it can help reduce freezes on certain device models.

---

## 14. Profiles and Playlists

### 14.1 Where to find profiles and playlists

On Movies/Series and TV screens, the top-left area shows an avatar and a profile name.  
Selecting it opens the Profile screen.

### 14.2 Profile management

On the Profile screen, you can:

- Select a profile to make it active
- Edit a profile (rename or change image)
- Add a profile

> ⚠️ WARNING: Important rule  
> When you add a profile, you must also add a new playlist for that profile.

### 14.3 Playlist management

From the Profile screen, a button opens playlist management. You can also reach Playlists from the playlist icon in the group drawer.

On the Playlists screen, you can:

- Edit playlist data (server address, username, password, etc.)
- Add a new playlist
- Delete a playlist (trash icon)

> ⚠️ WARNING: Deletion rule  
> You can delete only a playlist that is not currently active. If you have only one playlist, add a new one first, then delete the old one.

### 14.4 Switch the active playlist

Only one playlist can be active at a time.  
To switch, select the checkmark icon on the playlist you want to activate.  
Movies/Series and TV content will refresh to match the active playlist.

---

## 15. Settings

### 15.1 General information screen

The default Settings screen includes playlist information such as:

- App edition (free, premium, etc.)
- Playlist expiry date (provider subscription) and remaining days
- Content counts (movies, series, channels, programs)
- Last update date
- Other relevant playlist details

### 15.2 Playlist & update

A dedicated section allows you to:

- Manage your playlists
- Update the active playlist
- Update multiple playlists (select the playlists to update)
- Run a manual update by choosing which content types to refresh, then selecting Update

Typical update duration:

- Often 1 to 5 minutes

Scheduling:

- Default update time: 4:00 AM
- You can change the scheduled update time in the Playlist & update section

### 15.3 Preferences***

> ℹ️ INFO: Premium feature  
> Preferences include Premium options (***).

Examples of available preferences include:

- Application language
- Time format: 12h or 24h
- Number of channels shown in the TV Favorites panel
- Number of channels shown in the TV History panel
- History threshold: delay before adding, or never
- VOD: completion percentage required to mark a movie as watched
- Display a 'watched' tag on movie posters when you completed a movie
- EPG time offset (when programs are not aligned)
- Replay time offset (when replay launches content shifted by 1 to 12 hours)
- Define a user-agent (VOD & live)
- Show a group “ALL” in the vod section : displays all the contents in one place, one line = one group
- And many other options (with always more to come)

### 15.4 Group management (movies/series/channels)***

> ℹ️ INFO: Premium feature  
> Group management is a Premium feature (***).

These screens let you:

- Rename groups
- Reorder groups
- Hide groups  See Group visibility management section

> ⚠️ WARNING: Hidden groups and search  
> If you hide a group, its content will never appear in Search results.

Gestures:

- Rename: long press on the group
- Reorder: select, then move up/down (focus-based UI)
- Use tabs (movies/series/channels) to manage groups by content type

### 15.5 Channel management***

> ℹ️ INFO: Premium feature  
> Channel management is a Premium feature (***).

Same principle as group management:

- Reorder channels + favorites
- Rename channels
- Hide channels

- Use the right arrow then Up/Down to move channels
- One press to hide
- Long press to rename

### 15.7 Connection test

This section helps you verify:

- That your provider responds correctly
- Your playlist expiry date (also visible on the general information screen)

### 15.8 App version and updates

A section to:

- Check whether an app update is available
- Redirect you to update
- On Fire TV: download the update inside the app (platform-specific behavior)

### 15.9 Subscription screen (Android TV vs Fire TV)

The subscription screen differs by platform:

Android TV (Google Play)

- Subscriptions and purchases are managed through Google Play
- Maximum 5 devices, all linked to the same Google account used for purchase

Fire TV

- Premium activation uses a code (no Google Play subscription flow)
- Maximum 5 devices

How to get a Premium code for Fire TV

- Install the mobile app Wave IPTV mobile (Google Play on phone/tablet)
- Upload your playlist in the mobile app
- Open Settings in the mobile app, then choose Buy TV code (bottom of the menu)
- Complete payment
- Receive the code a few seconds later
- Enter the code on your TV to activate Premium

### 15.10 Remote mapping

Remote mapping lets you assign actions to remote buttons:

- Color buttons
- Navigation buttons
- Action gestures (single press, double press, etc.)

This is how you customize shortcuts used in the TV player and the EPG.

---

## 16. Premium edition: what you get (*** features) and free trial

Premium features are marked with *** throughout the guide.  
Premium is available with a 14-day free trial inside the app (no payment required to start).

How to start the trial:

- Select a Premium feature or Premium section in the app
- The paywall appears
- Start the 14-day trial

> ℹ️ INFO: Trial behavior  
> The 14 days start as soon as you activate the trial. No payment is charged automatically at the end, unless you voluntarily subscribe or purchase Premium.

### 16.1 Premium advantages (at a glance)

Premium is designed for power users who want faster navigation, more personalization, and better day-to-day comfort.

- Personalization: custom groups, sorting, reordering and hiding of groups/channels
- Convenience: favorites and history panels, enhanced player navigation
- Control: deeper preferences (EPG/replay offsets, history thresholds, watched markers)

### 16.2 List of Premium features in this guide

The following capabilities are explicitly marked as Premium (***):

- Favorites and History (VOD)***
- Custom Groups***
- OpenSubtitles in the VOD player***
- VOD player left/right side panels***
- TV player side panels***
- TV player advanced zapping view***
- TV Favorites and TV History panels***
- TV long-press directional actions***
- Preferences***
- Group management***
- Channel management***
- Reorder favorite channels***

---

## 17. Troubleshooting

### 17.1 Playlist import

- If nothing happens after QR transfer (30s+): close the TV app, reopen it, and try again (server may be busy).
- Link error: check http vs https (remove the 's' if needed).
- Link error: remove leading/trailing spaces around the URL.
- Very long import: large playlists take longer. Let insertion complete.

### 17.2 Voice search

- Voice search does not work if your remote has no microphone or if voice input is not available on your device.

### 17.3 Replay issues

- If there is no clock icon on the channel, replay is not supported.
- If replay is time-shifted: adjust replay offset in Preferences (up to 12 hours).

### 17.4 EPG time shift

- If the EPG grid is not aligned with your device time, adjust the EPG offset in Preferences.

### 17.5 Freezes when switching preview/full screen

- Try the Safe transition option (note: it causes a 1 to 2 second audio/video cut).

### 17.6 Audio out of sync

- Use the audio delay setting (positive or negative) in the player options.

### 17.7 Some channels have no audio

- Try software audio decoding (TV player advanced settings).
- Note: software audio decoding is incompatible with audio passthrough (it is disabled automatically when passthrough is enabled).

### 17.8 External playback (VLC)

- The external player option appears only if an external player is installed on the device.

---

## 18. Glossary

- EPG: Electronic Program Guide, TV guide showing programs per channel and schedule.
- VOD: Video On Demand, movies and series.
- Replay: playback of past programs (if supported by the channel).
- M3U: IPTV playlist format accessible via a URL.
- Xtream Codes: connection method using server URL, username, and password.
- Focus: the currently selected item in the Android TV interface.
- Drawer menu: a side panel listing groups or categories.
- Audio passthrough: sends audio directly to a compatible AV receiver.
- Auto frame rate: automatically matches display refresh rate to the content frame rate.
- EPG/Replay offset: time correction when guide or replay is not aligned.
```
