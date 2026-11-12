# DMD1 Backup Privacy Policy

Effective date: November 12, 2026

DMD1 Backup is a personal backup application operated by
Matthew Maune for his own research workspace.

## Data accessed and purpose

The application uses read-only Google Drive authorization to
retrieve file contents and metadata for backup and recovery.
Although authorization permits reading files accessible to the
connected account, backup operations are configured to target
the designated research workspace.

## Storage and protection

Downloaded files are staged on the owner's Windows computer.
Staging files and restore-test copies are not encrypted by restic.
Backup snapshots are encrypted by restic and stored on an external
storage device.

Google authorization tokens are stored locally by rclone.
A local copy of the backup password is protected using Windows
Data Protection API encryption.

## Sharing and use

The backup application does not sell Google user data, use it
for advertising, or transmit it to this public website.
Its purpose is backup, integrity checking, and recovery.

This website contains only application information. GitHub hosts
the website and may process visitor connection information under
its own privacy statement.

## Retention and control

Backup copies remain until the owner removes them under the
project's retention procedures. Disconnecting Google access
does not automatically delete existing local copies or backups.

The owner can revoke the application's access through Google
Account settings.

## Contact

For questions, use the developer contact email displayed on
the application's Google authorization consent screen.

[Home](index.html)
