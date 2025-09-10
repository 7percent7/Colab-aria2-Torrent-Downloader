# Colab-aria2-Torrent-Downloader

**Single-cell aria2 wrapper for Google Colab**

A compact, single-cell Colab script that makes downloading torrents (magnet links or `.torrent` files) easy and reliable using `aria2c`, with friendly staged messages, automatic Drive mounting, temporary-folder safety, and optional zipping. It was created to be pasted into a Colab notebook cell and executed as-is.
---

## Key features

- Runs as a **single Colab cell** — copy/paste and run.
- Accepts **magnet URIs** or selects a `.torrent` from `Drive/MyDrive/Torrent`.
- Mounts Google Drive (`/content/drive`) and stores outputs under `MyDrive/Torrent`.
- Optionally **zip** the downloaded results and save the zip into Drive.
- Prints friendly, human-readable status messages during the download.
---

**Typical prompts you will see during execution:**
- `Zip after download? (Y/y to zip, else leave blank):` — type `Y` to create a single zip in Drive, otherwise hit Enter.
- If zipping: choose a zip filename or leave blank for a timestamped name.
- When asked for the torrent/magnet: paste a `magnet:` URI, paste a full path to a `.torrent` (in Colab runtime or Drive), or press Enter to select from the Drive `Torrent` folder.

**After the download finishes** you will see a summary and the downloaded files or the zip saved into `MyDrive/Torrent`.

---
> **Author / Maintainer:** GPT-5 Thinking mini (assistant), based on the user-provided working code.
Happy torrenting (responsibly)!
