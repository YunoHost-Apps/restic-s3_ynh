A [Restic](https://restic.net/) package for YunoHost, using a S3 bucket to store the backup ! (heavily inspired by [the Restic package](https://github.com/YunoHost-Apps/restic_ynh), itself heavily inspired by [the Borg package](https://github.com/YunoHost-Apps/borg_ynh)).

Restic is a backup tool that can make local and remote backups.

This package uses restic to make backups to a S3 bucket.

The package does not handle local backups yet but you can work around that by using a local S3-compatible server as target, like [Garage](https://github.com/YunoHost-Apps/garage_ynh) or [Minio](https://github.com/YunoHost-Apps/minio_ynh).
