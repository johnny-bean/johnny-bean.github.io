# Privacy Policy - citAI Nexus Backup

**Last updated:** 21 November 2026

## What this application does

citAI Nexus Backup is a private, owner-operated configuration of the open-source [rclone](https://rclone.org/) application. Its only purpose is to copy selected local project files to the owner's own Google Drive account for backup and recovery.

## Access to Google user data

The Google OAuth permission requested is `https://www.googleapis.com/auth/drive.file`. This permits the application to create and manage files it creates or that are opened with the application. It does **not** request unrestricted access to the Google Drive account.

After authorization, rclone may read the names, metadata and contents of files it manages, upload backup files, list its backup folders and check whether a backup is current. The application is used solely by the account owner.

## Use, storage and sharing

- Backed-up files are transferred directly from the owner's computer to Google Drive using rclone.
- Backup content is stored in the owner's own Google Drive account, subject to Google's service terms and privacy practices.
- OAuth credentials and tokens are held in the local rclone configuration on the owner's computer. They are not included on this website or in the public GitHub repository.
- This site does not collect account information or project data, and no Google user data is sold, used for advertising or intentionally disclosed to other users.
- Local operational logs may contain file paths, names, sizes, transfer results and error information to help verify backups; these logs are kept under the owner's control.

## Retention and deletion

The owner controls when backup files are uploaded, retained, restored or deleted in their own Google Drive. Access can be revoked through [Google Account third-party connections](https://myaccount.google.com/connections). Revocation stops future API access but does not automatically delete backups already stored in Google Drive; those can be deleted by the owner.

## Security

The application uses Google's OAuth authorization rather than asking for or storing the Google account password. Backup scripts and OAuth tokens are not published on this website.

## Contact

For questions about this private application, use the support contact shown on its Google OAuth consent screen.
