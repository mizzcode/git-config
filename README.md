# Git Config

## Config User dan Email Git
`git config --global user.name "Misbahudin"`
`git config --global user.email "mizzc0d3@gmail.com"`

## Config Visual Studio Code untuk menjadikan default editor untuk Git
`git config --global core.editor "code --wait"`

### Config Difftool untuk Visual Studio Code
`git config --global diff.tool "default-difftool"`
`git config --global difftool.default-difftool.cmd "code --wait --diff \$LOCAL \$REMOTE"`

### Melihat Seluruh Configuration
`git config --list --show-origin`
