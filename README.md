# Resolver

VB6 host tool (`Resolver.exe`): resolves hostname to IP and reverse via GetHostX, optional PingX continuous ping, and NetHostTime sync/display of remote host time. Open `Resolver.vbp` in the VB6 IDE (needs GetHostX.ocx, PingX.ocx, NetHostTime.dll).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Resolver` (`Resolver.vbp`) | VB6 | WinForms exe | DNS resolve, ping, and host-time sync UI |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Resolver.vbp`

## Requirements

- Visual Basic 6.0 IDE
- GetHostX.ocx, PingX.ocx, and NetHostTime.dll (companion ActiveX/DLL dependencies)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Resolver`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
