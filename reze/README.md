# Reze

A custom pixel-style animated Codex pet.

## Install

1. Download this `reze` folder.
2. Copy the folder to your Codex pets directory:

```powershell
$dst="$env:USERPROFILE\.codex\pets\reze"
New-Item -ItemType Directory -Force -Path $dst
Copy-Item ".\pet.json" "$dst\pet.json" -Force
Copy-Item ".\spritesheet-running-phone.webp" "$dst\spritesheet-running-phone.webp" -Force

3.Restart Codex, or reselect the Reze pet so Codex reloads the spritesheet.

## Files
pet.json: pet manifest
spritesheet-running-phone.webp: animated pet spritesheet
contact-sheet-running-phone.png: preview of all animation states
