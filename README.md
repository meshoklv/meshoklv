<picture>
  <source media="(prefers-color-scheme: dark)" srcset="card-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="card-light.svg">
  <img alt="tmux session meshoklv: featured projects ash, madeira-kit, vibenokia, chamele0nx, pocket-agent, handgrab, thumbmux, opencode-steroids; more tools; open source in Madeira and wine." src="card-light.svg" width="100%">
</picture>

Developer building AI agents, iOS apps and network tools - and getting games to run on hardware that was never meant for them.

## Featured projects

### 🎮 Games on unusual hardware

| | |
|---|---|
| **[ash](https://github.com/meshoklv/ash)** | A from-scratch C engine that runs a cut-down Dark Souls 1 on a real PSP. Bring your own copy. |
| **[madeira-kit](https://github.com/meshoklv/madeira-kit)** | Guide and tooling for running heavy Windows x64 games on iPhone via Madeira (FEX-Emu + Wine + DXMT). |
| **[vibenokia](https://github.com/meshoklv/vibenokia)** | Vibe-code with Claude from a Nokia 3310: a J2ME terminal client, a small server, and 41 mini games. |

### 🤖 AI agents & tooling

| | |
|---|---|
| **[pocket-agent](https://github.com/meshoklv/pocket-agent)** | A coding agent for iPhone. The language model runs fully on the device, so your files never leave the phone. |
| **[opencode-steroids](https://github.com/meshoklv/opencode-steroids)** | Safety layer for the opencode coding agent: instant risk triage plus a multi-model review board that can veto dangerous tool calls. |
| **[blastbench](https://github.com/meshoklv/blastbench)** | Will your AI coding agent break production on a vague ticket? A Docker sandbox benchmark for blast radius. |
| **[thumbmux](https://github.com/meshoklv/thumbmux)** | Mobile-first, password-protected web terminal for tmux and AI coding agents: tabs, swipe scroll, uploads, voice. |
| **[claude-statusline](https://github.com/meshoklv/claude-statusline)** | A fast, configurable Claude Code status line: context bar, 5-hour and weekly limits, burn-rate warning, cost, git. |
| **[claude-native-timestamps](https://github.com/meshoklv/claude-native-timestamps)** | VS Code extension that shows the date and time of every message in the native Claude Code chat panel. |

### 🔒 Networking & security

| | |
|---|---|
| **[chamele0nx](https://github.com/meshoklv/chamele0nx)** | A VPN transport that does not look like a VPN: HTTP/2 to a cover site, Chrome fingerprints, shaped TLS records. |
| **[nightwarden](https://github.com/meshoklv/nightwarden)** | Night watchman for Linux servers: detects Mirai-class implants and secret theft, traps intruders with honeytokens. |

### 🗣 Speech

| | |
|---|---|
| **[ru-voice-agent](https://github.com/meshoklv/ru-voice-agent)** | Self-hosted Russian voice agent: T-one STT, Silero VAD, any LLM, Piper/Kokoro/Fish TTS, WebSocket and browser UI. |
| **[ru-speech-bench](https://github.com/meshoklv/ru-speech-bench)** | Hands-on benchmark of 21 Russian TTS, STT and VAD engines: real numbers, scripts, license audit. |
| **[gigaam-dictation](https://github.com/meshoklv/gigaam-dictation)** | Offline voice typing for macOS: press a key, speak, the text appears at the cursor. |

### ✋ Interaction

| | |
|---|---|
| **[handgrab](https://github.com/meshoklv/handgrab)** | Grab, rotate and sculpt 3D objects in mid-air with bare hands, using the iPhone TrueDepth camera at 120 Hz. |

### 🤖 Bots

| | |
|---|---|
| **[botarium](https://github.com/meshoklv/botarium)** | Six ready-to-run Telegram bots (voice summaries, tasks, image gen, booking, alerts) with one-command Docker Compose. |

## Open-source contributions

Merged into [Madeira](https://github.com/willfaust/Madeira) (x86-64 Windows PC games on non-jailbroken iOS via FEX-Emu + Wine + DXMT) and its Wine fork:

- [Madeira#148](https://github.com/willfaust/Madeira/pull/148) ntdll: count only back-to-back identical fault redeliveries per thread
- [Madeira#149](https://github.com/willfaust/Madeira/pull/149) win32u iOS: make a process's main window foreground while it polls XInput
- [Madeira#150](https://github.com/willfaust/Madeira/pull/150) Touch controls: a touch that misses the controls is no mouse while a controller layout is shown
- [wine#18](https://github.com/willfaust/wine/pull/18) ntdll ARM64EC: leave the syscall callback on the [exec-req] return path
- [wine#19](https://github.com/willfaust/wine/pull/19) ntdll: load the builtin XInput even when the game ships its own copy

I also got Dark Souls Remastered (PC) playable on iPhone Air with no game file changes: [write-up](https://github.com/willfaust/Madeira/issues/56).

`~ $` [t.me/meshoklv](https://t.me/meshoklv) · [instagram.com/meshoklv](https://instagram.com/meshoklv) · [github.com/meshoklv](https://github.com/meshoklv)
