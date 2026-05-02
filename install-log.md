# video-use skill installation

Installed from https://github.com/browser-use/video-use

## What was installed

- Repository cloned to `~/Developer/video-use`
- Python dependencies installed via `uv sync`
- `ffmpeg` and `ffprobe` installed (v6.1.1)
- `yt-dlp` installed
- Skill registered at `~/.claude/skills/video-use`

## Pending configuration

Add your ElevenLabs API key to `~/Developer/video-use/.env`:

```
ELEVENLABS_API_KEY=your_key_here
```

Get a key at https://elevenlabs.io/app/settings/api-keys
