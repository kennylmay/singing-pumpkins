# Singing Pumpkins

Project talking, singing jack-o'-lantern faces onto real pumpkins with an ordinary projector.

Singing Pumpkins is a single web page that draws up to three animated pumpkin faces on a black background. Black means no light, so when you aim a projector at your pumpkins, only the glowing eyes, noses and mouths land on them. The eyes look around and blink, the mouths move with your music, and the faces can bounce along to the beat.

<!-- Add a screenshot or a short GIF of the faces here, for example: ![Three pumpkin faces](screenshot.png) -->

## What you need

- A computer with **Chrome or Edge** (desktop versions work best)
- A **projector**, ideally as a second display
- One to three **pumpkins** with smooth faces, in a fairly dark space
- Optional: an MP3, a video or music playing in another browser tab, or a microphone

There is nothing to install and nothing to build. The whole program is one file: `Pumpkin Projector.html`.

## Quick start

1. Download `Pumpkin Projector.html` from this repository.
2. Double-click it to open it in Chrome or Edge.
3. Connect your projector and set your computer to **extend** the display, so the projector acts as a second screen.
4. Drag the browser window onto the projector screen and press **F** for fullscreen.
5. Press **Test talk** to see the mouths move without any audio.
6. Work through the four steps in the panel (see below) to line the faces up with your pumpkins and pick what they listen to.
7. Press **H** to hide the panel when you are ready to show it off.

> **Open the saved file on your computer.** If you run the page from inside another page or an online preview, the browser blocks tab sharing, the microphone and lyric lookups. A saved copy opened straight from your computer works.

## The four steps

The control panel guides you through four stages. You can jump between them with the numbered buttons at the top, or use Back and Next. Play, Stop and Test talk stay at the top of every step.

### 1. Sound and pumpkins

Choose how many pumpkins you are using (1, 2 or 3), then choose what each one listens to:

| Source | What it does |
| --- | --- |
| **Shared MP3** | One MP3 for the pumpkins that choose it |
| **Its own MP3** | A separate MP3 for just that pumpkin |
| **Tab audio** | Listens to a video or music playing in another browser tab |
| **Microphone** | Listens to the room, for example to a song playing on speakers |
| **Timed lyrics** | Moves the mouth to the words of a song, using lyrics with timestamps |

The setup for each sound appears right below, and only for the sounds you have actually chosen. You can mix them, for example two pumpkins on a tab and one on the microphone. If several pumpkins share a sound, tick **Take turns** to have them trade lines instead of all talking at once.

This step also has the sound sensitivity settings: how closely the mouths follow the sound, how well it picks out a voice from the music, and how beats are detected for dancing.

### 2. Place the faces

Turn on **Show alignment guides**, then use the sliders for each pumpkin (left/right, up/down, size and tilt) until each face sits on its pumpkin. Press **Test talk** while you adjust to see the mouths move.

### 3. Style the faces

- **All pumpkins:** light color, glow, candle effect and flicker, eye speed, blinking, pupils, noses, how round the mouth gets, and the dancing (bounce height, sway and snappiness).
- **Each pumpkin:** its own eye shape and size, mouth style and nose. The **Use the three-face look on all** button applies a ready-made set of three different faces.

### 4. Show it

Go fullscreen, hide the panel, move the panel to the other side of the screen, and save your setup.

## Faces and mouths

- **Eyes** come in plain shapes (round, tall oval, angry slant, triangle, heavy lid, big oval) and in "notch" versions. The notch eyes have a small triangle cut into the rim that slides around the edge toward wherever the eye is looking, like a pupil that stays attached to the pumpkin wall.
- **Mouths** come in six styles: a smile that rounds into an O, a cartoon grin with a tongue, buck teeth, a full row of teeth, a jagged jack-o'-lantern mouth, and a simple round O. The teeth are cut into the glowing shape, so they blend into the dark, just like a real carving.
- **Candle look** gives each shape a hot center, deeper orange edges, a dark inner rim and a gentle flicker, so it looks lit from inside.

## Timed lyrics

Timed lyrics make the mouths follow the words of a song. Each line is split into syllables, and each syllable picks a mouth shape (ah, ee, oh, oo, and closed lips for b, m and p).

1. Set a pumpkin's source to **Timed lyrics**.
2. Add lyrics in standard timed format, one line per row with a time before it, like `[0:12.50]`. Lines without times are spaced evenly.
3. Start the clock in one of three ways:
   - **Start lyrics** when the song reaches your start point.
   - **Wait for sound**, which starts it by itself the moment the first sound is heard.
   - Load the song as the **shared MP3** and tick **Follow the MP3's position**. The clock then follows the MP3 exactly, including pauses and skips.
4. If the mouths run early or late, use the **Earlier / Later** nudge buttons.

You can also choose a **sound feed** (shared MP3, tab audio or microphone) for the lyrics. The feed makes the faces dance to the beat, lets the mouths follow the real loudness a little, and lets Wait for sound know when the song begins.

### Finding lyrics

When you load the shared MP3, the page reads its title, artist and album from the file's tags and can look the song up on [LRCLIB](https://lrclib.net), a free, community-built database of synced lyrics. If the file has no tags, it guesses from the file name, such as `Artist - Title.mp3`. You can correct the artist and title and press **Find lyrics** at any time.

- Only the artist, title, album and song length are sent, and only from your browser.
- Lookups need an internet connection and the page opened from your computer.
- Not every song has timed lyrics there, and the timings come from the community, so use the nudge buttons if needed.
- Lyrics belong to their authors and publishers. This program does not include any lyrics. It only uses the words to choose mouth shapes and never shows them on the projection.

## Saving

- Your settings **save themselves** in the browser as you change them.
- **Saved setups** let you keep named versions, for example one per party, and load or delete them later.
- **Remembered MP3s** are kept in the browser too, so your songs are still loaded next time. You can switch this off, or clear them, in step 4.

Browser storage belongs to the browser and the place you open the page from. If you move the file, switch browsers or clear your browsing data, the saved settings and MP3s will not follow.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| **H** | Hide or show the control panel |
| **F** | Fullscreen on or off |
| **Space** | Play or pause (when no text box is selected) |
| Double-click the stage | Show or hide the panel |

The panel also fades out on its own when the mouse is still, so it does not stay on your pumpkins.

## Tips for a good show

- Use a **dark room** and a projector with good brightness. The darker the background, the more the faces glow.
- Pale or orange pumpkins with smooth faces work well. Try the light color setting if the glow looks washed out.
- Use **Show alignment guides** and **Test talk** to line everything up before guests arrive.
- Turn up **Glow** and **Candle look** for a softer, warmer look, or lower them for crisper shapes.
- If you play music on a separate device, point the **microphone** at the speakers, or use **tab audio** if the music is in a browser tab on the same computer.

## Troubleshooting

| Problem | What to try |
| --- | --- |
| The mouths do not move | Press **Test talk** to check the faces. Then make sure a sound source is set up for that pumpkin in step 1 and that audio is playing. |
| Tab audio asks for permission but captures nothing | Use desktop Chrome or Edge, choose a **browser tab** (not a window or screen) and tick the option to share tab audio. |
| Microphone or tab sharing is blocked | Open the saved file directly on your computer instead of an online preview or embedded page. |
| Lyric lookup fails | You need to be online with the page opened from your computer. Otherwise, search lrclib.net yourself and paste the lyrics. |
| The lyrics are early or late | Use the nudge buttons, or follow the MP3's position if the song is loaded as the shared MP3. |
| A pumpkin shows nothing | It may be switched off. Use the **1 / 2 / 3 pumpkins** buttons in step 1. |
| The panel is gone | Press **H**, or move the mouse and click **Show controls**. |
| Saved settings or MP3s disappeared | Browser data was cleared, or the file was opened from a different place or browser. |

## Good to know

- Spotify and other streaming apps do not allow other programs to read their audio, so to react to a song from one of them, use **tab audio** (if it plays in a browser) or the **microphone**. The program also does not use the Spotify API.
- MIDI files are not supported.
- The page can use Google Fonts for the panel title, but it works fine without them.

## Project files

| File | Purpose |
| --- | --- |
| `Pumpkin Projector.html` | The whole program: drawing, sound analysis and controls, all in one file |
| `README.md` | This guide |

Have fun, and happy Halloween!
