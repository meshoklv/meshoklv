<picture>
  <source media="(prefers-color-scheme: dark)" srcset="card-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="card-light.svg">
  <img alt="tmux session meshoklv: featured projects chamele0nx, pocket-agent, handgrab, gigaam-dictation; open source in Madeira and wine; coming next ash, vibenokia, dsr-kit." src="card-light.svg" width="100%">
</picture>

Developer building AI agents, iOS apps and network tools - and getting games to run on hardware that was never meant for them.

## Featured projects

| | |
|---|---|
| **[chamele0nx](https://github.com/meshoklv/chamele0nx)** | A VPN transport that does not look like a VPN: its traffic is shaped to look like someone using a website. |
| **[pocket-agent](https://github.com/meshoklv/pocket-agent)** | A coding agent for iPhone. The language model runs fully on the device, so your files and tasks never leave the phone. |
| **[handgrab](https://github.com/meshoklv/handgrab)** | Virtual hands from the TrueDepth camera: pinch, carry and throw objects in 3D at 120 Hz. |
| **[gigaam-dictation](https://github.com/meshoklv/gigaam-dictation)** | Offline voice typing for macOS: press a key, speak, the text appears at the cursor. |

## Open-source contributions

Merged into [Madeira](https://github.com/willfaust/Madeira) (x86-64 Windows PC games on non-jailbroken iOS via FEX-Emu + Wine + DXMT) and its Wine fork:

- [Madeira#148](https://github.com/willfaust/Madeira/pull/148) ntdll: count only back-to-back identical fault redeliveries per thread
- [Madeira#149](https://github.com/willfaust/Madeira/pull/149) win32u iOS: make a process's main window foreground while it polls XInput
- [Madeira#150](https://github.com/willfaust/Madeira/pull/150) Touch controls: a touch that misses the controls is no mouse while a controller layout is shown
- [wine#18](https://github.com/willfaust/wine/pull/18) ntdll ARM64EC: leave the syscall callback on the [exec-req] return path
- [wine#19](https://github.com/willfaust/wine/pull/19) ntdll: load the builtin XInput even when the game ships its own copy

I also got Dark Souls Remastered (PC) playable on iPhone Air with no game file changes: [write-up](https://github.com/willfaust/Madeira/issues/56).

## Coming next

- **ash** - the Dark Souls engine running on a real PSP
- **vibenokia** - Claude on a Nokia 3310
- **dsr-kit** - Dark Souls Remastered on iPhone, toolkit and notes

`~ $` [t.me/meshoklv](https://t.me/meshoklv) · [instagram.com/meshoklv](https://instagram.com/meshoklv) · [github.com/meshoklv](https://github.com/meshoklv)
