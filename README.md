# ChornobylTogether

Co-op mod for S.T.A.L.K.E.R. 2: Heart of Chornobyl (Steam). This repository hosts the launcher builds; the
launcher updates itself from the releases here.

## First install

1. Download `ChornobylTogether.exe` from the [latest release](../../releases/latest).
2. Close the game, run `ChornobylTogether.exe`, click **Install / update mod**.
3. Back up your saves with **Back up my saves** before playing.

## Updates

Every time the launcher starts it checks this page. When a newer build exists it asks, downloads it, checks the
SHA-256 that GitHub publishes for the file, swaps itself and restarts, then reinstalls the mod files (close the game
first). Nothing is installed if the check fails. `ChornobylTogether.exe --update` does the same without asking.

All players need the same build to connect.

Contains no game files. You need your own copy of the game.
