# Exchange

CSC VB6 Exchange tracking-log extract tool (`Exchange Tracking.exe`) that converts Exchange Server `tracking.log` files (YYYYMMDD.log) into CSV. Supports GUI date-range selection or command-line `/s:` `/d:` `/m:` modes, optional delete-before-extract, and all-data vs subset extract. Tracking parse helpers credited to Brian Feige.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TrackingLogExtract` (`Exchange Tracking.vbp`) | VB6 | WinForms exe | Exchange tracking.log to CSV |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Exchange Tracking.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMDLG32.OCX`
  - `MSCAL.OCX`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Exchange`.
Company names in project files: CSC. Original extract procedure credited to Brian Feige.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
