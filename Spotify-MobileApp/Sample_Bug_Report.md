# Sample Test Defects – Spotify Mobile Application

Note: All defects listed below are simulated for portfolio purposes and may not exist in the actual Spotify app.

Project: Spotify mobile application

## Defect 1 – Network Switch Playback Issue

| Field                  | Details                                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------------- |
| **Defect ID**          | SPOTIFY-BUG-001                                                                                               |
| **Title**              | Playback pauses unexpectedly when switching from Wi-Fi to mobile data                                         |
| **Environment**        | Mobile App, Android 13, Samsung Galaxy S21, Spotify v8.9.x, Wi-Fi → Mobile Data, Free & Premium               |
| **Severity**           | High                                                                                                          |
| **Priority**           | P2                                                                                                            |
| **Preconditions**      | User logged in, active internet, playback started on Wi-Fi                                                    |
| **Steps to Reproduce** | 1. Open Spotify app<br>2. Play a song<br>3. Turn off Wi-Fi<br>4. Switch to mobile data<br>5. Observe playback |
| **Expected Result**    | Music continues playing seamlessly                                                                            |
| **Actual Result**      | Playback pauses and requires manual Play                                                                      |
| **Frequency**          | Intermittent (3/5 attempts)                                                                                   |
| **Attachments**        | Screen recording (optional)                                                                                   |
| **Notes**              | Issue occurs more with slower network handoff; no error message                                               |

## Defect 2 – UI Issue: Overlapping Text on Playlist Titles

| Field                  | Details                                                                                                                            |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Defect ID**          | SPOTIFY-BUG-002                                                                                                                    |
| **Title**              | Playlist titles overlap with artist names on small screen devices                                                                  |
| **Environment**        | Mobile App, iOS 16, iPhone SE (2nd Gen), Spotify v8.9.x                                                                            |
| **Severity**           | Medium                                                                                                                             |
| **Priority**           | P3                                                                                                                                 |
| **Preconditions**      | User logged in, playlist with long title exists                                                                                    |
| **Steps to Reproduce** | 1. Open Spotify app<br>2. Navigate to "Your Library"<br>3. Select a playlist with a long title<br>4. Observe title and artist text |
| **Expected Result**    | Playlist title and artist names display correctly without overlapping                                                              |
| **Actual Result**      | Playlist title overlaps with artist name, causing truncation and unreadable text                                                   |
| **Frequency**          | Consistent on devices with small screen width                                                                                      |
| **Attachments**        | Screenshot showing overlapping text                                                                                                |
| **Notes**              | Impacts readability and UI consistency                                                                                             |



## Defect 3 – Usability Issue: Inconsistent Volume Control Behavior

| Field                  | Details                                                                                                                    |
| ---------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **Defect ID**          | SPOTIFY-BUG-003                                                                                                            |
| **Title**              | Volume slider sometimes does not update actual playback volume                                                             |
| **Environment**        | Web Player, Chrome v120, Windows 11                                                                                        |
| **Severity**           | Medium                                                                                                                     |
| **Priority**           | P3                                                                                                                         |
| **Preconditions**      | User logged in via web player                                                                                              |
| **Steps to Reproduce** | 1. Open Spotify web player<br>2. Play a song<br>3. Adjust volume slider to 50%<br>4. Refresh the page<br>5. Observe volume |
| **Expected Result**    | Volume slider adjusts playback volume accurately                                                                           |
| **Actual Result**      | Slider visually shows 50%, but playback remains at previous volume until manually adjusted again                           |
| **Frequency**          | Occasional (2/5 attempts)                                                                                                  |
| **Attachments**        | Screen recording showing discrepancy                                                                                       |
| **Notes**              | Could confuse users and affect listening experience                                                                        |

## Defect 4 – Accessibility Issue: Missing Alt Text for Album Covers

| Field                  | Details                                                                                                                       |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Defect ID**          | SPOTIFY-BUG-004                                                                                                               |
| **Title**              | Album cover images missing alt text for screen readers                                                                        |
| **Environment**        | Web Player, Chrome v120, NVDA screen reader, Windows 11                                                                       |
| **Severity**           | Low                                                                                                                           |
| **Priority**           | P4                                                                                                                            |
| **Preconditions**      | User logged in via web player, screen reader enabled                                                                          |
| **Steps to Reproduce** | 1. Open Spotify web player with NVDA enabled<br>2. Navigate through playlists and albums<br>3. Listen to screen reader output |
| **Expected Result**    | Screen reader announces album name or artist for each album cover                                                             |
| **Actual Result**      | Screen reader only announces “image” or skips album cover entirely                                                            |
| **Frequency**          | Consistent                                                                                                                    |
| **Attachments**        | NVDA audio recording                                                                                                          |
| **Notes**              | Accessibility issue for visually impaired users                                                                               |
