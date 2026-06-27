# ElevenLabs Multi-Key Studio

## All Your Accounts In One Place

ElevenLabs Multi-Key Studio is a browser-based long-form text-to-speech application that combines multiple ElevenLabs API keys into a single generation workflow.

Instead of manually switching between accounts when credits run out, simply add all of your API keys and let the application automatically select the best key for each request.

Generate audiobooks, narrations, podcasts, YouTube voiceovers, educational content, and other long-form audio without constantly monitoring account usage.

---

## Features

### Multi-Key Management

- Add one or multiple ElevenLabs API keys
- Add more keys at any time
- Duplicate key detection
- Remove keys individually
- Test API keys
- Automatic key validation
- Key health monitoring

### All Your Accounts In One Place

Add API keys from as many ElevenLabs accounts as you like.

The application automatically combines available usage across all supplied keys and treats them as a single generation pool.

No account management is required.

Simply paste your API keys and start generating.

### Automatic Key Rotation

When a key becomes unavailable or does not have enough remaining usage for the next generation:

1. The application automatically selects another available key
2. Generation continues without interruption
3. No manual account switching is required

### Long-Form Generation

Generate content far larger than the normal request limits.

The application automatically:

- Splits large scripts into chunks
- Preserves paragraph boundaries where possible
- Preserves sentence boundaries where possible
- Avoids cutting words in half
- Processes chunks sequentially

### Voice Browser

Automatically loads available ElevenLabs voices.

Features include:

- Voice search
- Voice filtering
- Default ElevenLabs voices
- Shared voices available to the supplied API keys

### Generation Planner

Before generation begins, the application estimates:

- Script length
- Estimated chunk count
- Available usage across all loaded keys
- Generation readiness

This helps prevent failed generations before processing starts.

### Progress Tracking

Live progress updates including:

- Current chunk
- Total chunks
- Active API key
- Generation progress percentage
- Status messages
- Estimated completion progress

### Guest Mode

No account is required.

Users can:

- Open the application
- Paste API keys
- Generate audio immediately

Refreshing the page removes all loaded keys.

### Remember Keys Mode

Optional browser-based storage.

When enabled:

- API keys are stored locally in the browser
- Keys automatically reload on future visits
- No server is required

---

## How It Works

### Step 1

Add one or more ElevenLabs API keys.

Example:

```text
sk_key_1
sk_key_2
sk_key_3
```

### Step 2

Choose a voice.

### Step 3

Paste your script.

### Step 4

Generate audio.

The application automatically:

- Splits large scripts into chunks
- Chooses the best available API key
- Rotates keys when necessary
- Tracks progress
- Produces downloadable audio

---

## Intended Use Cases

- YouTube narration
- Audiobooks
- Podcasts
- Educational content
- Documentary voiceovers
- Story narration
- Course creation
- Long-form speech generation
- AI voice workflows

---

## Technology Stack

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

## Privacy

The application does not provide API keys.

Users must supply their own ElevenLabs API keys.

Keys are stored only:

- In browser memory
- Or locally in browser storage when "Remember Keys" is enabled

No backend server is required.

No keys are shared with other users.

---

## Roadmap

Planned improvements include:

- Audio merging
- MP3 export improvements
- WAV export
- ZIP downloads
- Advanced voice search
- Usage analytics
- Enhanced generation planning
- Additional export formats

---

## License

MIT License

---

Built for creators who want all their ElevenLabs accounts in one place.
