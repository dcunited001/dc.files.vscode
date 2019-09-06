# dc.files.vscode

default settings for vscode. basically just `settings.json`.

### Setup

- create softlink from `$HOME/Library/Application
Support/Code/User/settings.json` to the merged `settings.json` for
that platform (mac/linux/etc)
- create softlink from `~/.config/.jsbeautifyrc` to `.jsbeautifyrc`

- TODO: script to merge `settings.all.json` with `settings.mac.json`
- TODO: collect list of extensions to install by default

- setup `../init/vscode.sh` with `code --install-extension <extension-id>`
