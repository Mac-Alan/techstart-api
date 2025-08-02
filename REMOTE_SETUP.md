# Remote Repository Setup

## Current Remotes
git remote -v
backup	git@github.com:Mac-Alan/techstart-api-backup.git (fetch)
backup	git@github.com:Mac-Alan/techstart-api-backup.git (push)
origin	git@github.com:Mac-Alan/techstart-api.git (fetch)
origin	git@github.com:Mac-Alan/techstart-api.git (push)
origin	git@github.com:Mac-Alan/techstart-api-backup.git (push)

## Tracking Branches
git branch -vv
  develop 26b9494 update version API
* main    ba82c8a [origin/main] Merge branch 'main' of github.com:Mac-Alan/techstart-api

## Fork Workflow Summary
- Original repository: https://github.com/Mac-Alan/awesome-calculator
- Fork repository: https://github.com/MacTestFist/awesome-calculator
- Upstream configuration: git remote add upstream git@github.com:Mac-Alan/awesome-calculator.git

## Backup Strategy
- Primary remote: origin
- Backup remote: backup
- Sync command: git remote set-url --add --push origin git@github.com:Mac-Alan/techstart-api-backup.git

## Lessons Learned
remote-репозитории позволяют синхронизировать свою работу с удалённым репозиторием,
а также получать все нововедения других разработчиков.
Они позволяют синхронизировать один локальный репозиторий с несколькими удалёнными.
