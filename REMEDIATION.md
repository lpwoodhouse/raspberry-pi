# Repository remediation — October 2026

Requires a separately verified download checksum, corrects the exporter listen-address syntax and adds daemon reload/restart handling. The checksum must be supplied for the selected release before use.

## Validation

Validation is limited to local parsing, fixtures and documentation checks as applicable. No live-system action was performed.

## Release and recovery

These changes are proposed through a review branch. Review behavior and prerequisites before merging or using operational scripts. Revert the change commit to recover ordinary code if necessary; **never restore exposed credentials or weaken access controls as a rollback shortcut**. No deployment, password rotation, repository visibility change or history rewrite is included.
