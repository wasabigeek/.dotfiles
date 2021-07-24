Technically more than dotfiles, very much a work-in-progress.

# Workflow
For a new MacOS machine, run in terminal:
- `curl --remote-name https://raw.githubusercontent.com/wasabigeek/.dotfiles/main/init`
- `sh init 2>&1 | tee ~/laptop.log`

Existing:
- clone this repo
- make changes in the repo
- run ./up
