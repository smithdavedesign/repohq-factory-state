# repohq-factory-state

Nightly backup of the RepoHQ factory's local state, written by `factory/bin/backup-state.sh` (Github-HQ). Restore: copy `ledger.jsonl`, `reports/`, `scout-reports/`, `value-labels/` and `queue/` back into `~/.repohq-factory/`.

Never here: secrets (env, keys), the context index (work data stays local), logs.
