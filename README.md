# pocketbase-starter-kit

Scripts (from package.json):

- `bun run serve`  (alias: `bun run s`)  
  Runs: `pocketbase serve --dir ./data/`

- `bun run clean`  (alias: `bun run c`)  
  Runs: `rm -rf data` — deletes the ./data directory

## Download PocketBase binary

- Go to: <https://github.com/pocketbase/pocketbase/releases>
- Download the file for your OS from the latest release:
  - Windows: `pocketbase_windows_amd64.zip`
  - macOS: `pocketbase_darwin_amd64.zip` (Intel) or `pocketbase_darwin_arm64.zip` (Apple Silicon)
  - Linux: `pocketbase_linux_amd64.zip`
- Extract the zip and place the `pocketbase` executable in your project folder (Windows executable: `pocketbase.exe`).
- Optional — add to PATH:
  - Windows: add the folder containing `pocketbase.exe` to your PATH environment variable (restart terminals).
  - macOS/Linux: move the executable to `/usr/local/bin/` or add its folder to PATH (ensure `chmod +x pocketbase`).
