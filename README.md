# .vscode configuration files (Windows)

## Setup

    # Add alias for push and pull of settings

    git config --global alias.vscpull  "!git -C $Env:APPDATA\Code\User init . ; git -C $Env:APPDATA\Code\User remote add origin https://github.com/ksjbrown/dotvscode.git ; git -C $Env:APPDATA\Code\User checkout main"
