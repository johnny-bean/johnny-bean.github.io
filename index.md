# citAI Nexus Backup

This is the informational homepage for **citAI Nexus Backup**, a personal desktop backup configuration using [rclone](https://rclone.org/) and the Google Drive API.

## Purpose

The application is used by its owner to maintain a backup of locally stored geospatial project files in the owner's own Google Drive account. It does not run a public online service or provide access to the owner's files to other users.

The backup runs from the owner's own computer. rclone transfers selected files directly between the local device and Google Drive after the account owner grants OAuth authorization.

## Google Drive access

The application requests the `drive.file` scope, which is limited to files created or opened with this application. It does not request access to all files in the account. The owner can revoke access in their [Google Account security settings](https://myaccount.google.com/connections).

This homepage does not contain any project data, backups, access credentials or OAuth tokens.

For details about data handling, see the [Privacy Policy](./privacy.html).
