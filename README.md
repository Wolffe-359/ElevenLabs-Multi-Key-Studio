# ElevenLabs Multi-Key Studio

A browser-based long-form text-to-speech studio powered by the ElevenLabs API.

Users provide their own ElevenLabs API keys and can generate long-form narration, audiobooks, videos, podcasts, and voiceovers directly in the browser.

---

## Features

### Multi-Key Management

- Add one or multiple ElevenLabs API keys
- Add additional keys at any time
- Duplicate key detection
- Remove keys individually
- Test keys
- Key status tracking

### Automatic Key Rotation

When a key runs out of credits or reaches a usage limit:

1. The current generation pauses
2. The next available key is selected automatically
3. Generation continues without user intervention

### Long-Form Generation

Generate scripts much larger than ElevenLabs' normal request limits.

The application automatically:

- Splits text into chunks
- Preserves sentence boundaries
- Preserves paragraph boundaries when possible
- Prevents mid-word cuts

### Voice Support

Built-in voices:

- Scotty (Australian English)
- Rachel

Custom voices:

- Any ElevenLabs Voice ID
- Shared voices
- Professional voices
- Cloned voices

### Progress Tracking

Live progress display:

- Current chunk
- Total chunks
- Current API key
- Estimated completion
- Generation status

### Usage Dashboard

Displays:

- Total keys loaded
- Active key
- Working keys
- Exhausted keys
- Estimated available generation capacity

### Storage Modes

#### Guest Mode

- No login required
- Keys stored in memory only
- Refreshing the page removes all keys

#### Remember Keys Mode

- Saves keys locally in browser storage
- Automatically restores keys on future visits
- No server required

---

## Planned Features

- Audio chunk merging
- ZIP downloads
- WAV export
- MP3 export
- Voice presets
- Script history
- Usage analytics
- Dark mode improvements

---

## Technology

Frontend:

- HTML
- CSS
- JavaScript

Hosting:

- GitHub Pages

API:

- ElevenLabs REST API

Storage:

- Browser LocalStorage

---

## Security

API keys are never hardcoded into the application.

Each user supplies their own ElevenLabs API keys.

Keys are stored only:

- In browser memory
- Or in local browser storage when "Remember Keys" is enabled

No backend server is required.

---

## Intended Use Cases

- YouTube narration
- Audiobooks
- Podcasts
- Educational content
- Long-form voiceovers
- AI voice workflows

---

## License

MIT License
