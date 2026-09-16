# DhiTV

A curated, shareable IPTV playlist for Maldivian TV channels.

## Playlist

`playlists/dhivehi.m3u` contains 10 entries, including:

| Channel | Group | Resolution |
|---------|-------|------------|
| Channel 13 | General | 1080p |
| Maldives TV | Travel | 720p |
| MMTV | General | 1080p |
| NTV | General | - |
| SSTV | General | 1080p |
| TV Maldives | General | - |
| VTV | News | 1080p |
| YES | News | - |
| Dhaaris TV | General | - |
| Raajje TV | General | - |

## How to use

Import `playlists/dhivehi.m3u` into your preferred IPTV player:

- **VLC**: Media → Open Network Stream → use `https://raw.githubusercontent.com/Saalhanga/dhivehi-iptv/main/playlists/dhivehi.m3u`
- **TiviMate**: Settings → Playlists → Add playlist → select file/URL
- **IINA**: File → Open URL → paste playlist URL
- **MPV**: `mpv --no-video --playlist=playlists/dhivehi.m3u`

## Notes

- Stream URLs may change without notice. If a channel fails, please open an issue with the updated URL.

## Testing locally

Open `players/hls-player.html` in a browser to test individual streams with HLS.js.

## Contributing

- Channels and URLs may change over time. Please open an issue or PR with updates.
- Keep the playlist minimal and curated. This is not intended to be a comprehensive global IPTV list.


