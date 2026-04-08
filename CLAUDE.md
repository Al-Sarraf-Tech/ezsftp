# CLAUDE.md — ezsftp

Bash script for provisioning and revoking chrooted SFTP users with dry-run support.

## Build

No compiled artifacts — shell script only.

```bash
bash -n ezsftp.sh
```

## Test

```bash
bash -n ezsftp.sh
shellcheck ezsftp.sh
bash ezsftp.sh --dry-run     # dry-run mode (if supported)
```

## Lint

```bash
shellcheck ezsftp.sh
```
