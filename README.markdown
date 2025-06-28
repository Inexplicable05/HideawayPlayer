# HideawayPlayer

HideawayPlayer is a sleek Rainmeter skin that integrates Spotify playback controls into the Windows taskbar, automatically hiding when Spotify is closed or fullscreen applications are active.

## Features

- **Taskbar Integration**: Seamlessly blends into the Windows taskbar like a native element.
- **Spotify Control**: Displays track title, artist, album art, progress, and volume controls for Spotify.
- **Auto-Hide**: Hides when Spotify is closed or inactive, keeping your desktop clean.
- **Fullscreen Detection**: Automatically hides during fullscreen applications (e.g., videos or games).
- **Customizable**: Adjust scaling and positioning via Rainmeter variables for a personalized experience.

## Screenshots

*Add screenshots here to showcase HideawayPlayer in action on the taskbar with Spotify active and during fullscreen mode.*

## Prerequisites

- **Rainmeter**: Version 4.5 or later (download from rainmeter.net).
- **WebNowPlaying Plugin**: Required for Spotify integration (install via WebNowPlaying).
- **Spotify**: Desktop app or web player with WebNowPlaying browser extension or Spicetify for compatibility.
- **Windows**: Optimized for Windows 10/11.

## Installation

1. **Install Rainmeter**: Download and install Rainmeter from rainmeter.net.
2. **Install WebNowPlaying Plugin**:
   - Download the WebNowPlaying plugin from its GitHub page.
   - Place it in your Rainmeter plugins folder (typically `C:\Users\<YourUser>\AppData\Roaming\Rainmeter\Plugins`).
3. **Download HideawayPlayer**:
   - Clone this repository or download the `.zip` file.
   - Extract the `HideawayPlayer` folder to your Rainmeter skins directory (usually `C:\Users\<YourUser>\Documents\Rainmeter\Skins`).
4. **Load the Skin**:
   - Open Rainmeter’s Manage window.
   - Find `HideawayPlayer\HideawayPlayer.ini` in the Skins tab and click "Load".
5. **Configure WebNowPlaying**:
   - Install the WebNowPlaying browser extension for your browser (e.g., Chrome, Firefox) or configure Spicetify for Spotify desktop.
   - Ensure Spotify is running and connected to WebNowPlaying.

## Folder Structure

- `HideawayPlayer\HideawayPlayer.ini`: Main skin configuration file.
- `HideawayPlayer\@Resources\`: Contains assets like `previous.png`, `play.png`, `pause.png`, `next.png`, and `Default.png`.

## Troubleshooting

- **Skin not appearing?** Ensure Spotify is running and WebNowPlaying is properly configured. Check Rainmeter’s Manage window for errors.
- **No album art?** Verify that `@Resources\Cover.png` is writable and WebNowPlaying is connected to Spotify.
- **Skin not hiding in fullscreen?** Confirm the `IsFullscreen` plugin is working; test with a fullscreen video or game.
- **Controls not responding?** Ensure the WebNowPlaying plugin is updated and compatible with your Spotify version.

## License

This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

## Contributing

Feel free to submit issues or pull requests on GitHub. Suggestions for improving compatibility or adding features are welcome!

## Credits

- Built with Rainmeter.
- Uses WebNowPlaying for Spotify integration.
- Fullscreen detection via the `IsFullscreen` plugin.