# PFO · Peak Financial Outlook

PFO is a household net worth and goals tracker that runs on your own computer. Your data stays there: there's no account to create and no bank connection.

This repository holds the installers only: no source code, and never anyone's data.

## Install

Go to the [latest release](https://github.com/smithsam7/pfo-releases/releases/latest) and download the right file from **Assets**. PFO isn't signed by Apple or Microsoft yet, so your computer will warn you the first time.

### Windows

Works on 64-bit Windows.

1. Download the file ending in `-windows-x64-setup.exe`.
2. Run it. If Windows says it protected your PC, click **More info**, then **Run anyway**.
3. PFO installs and opens. It doesn't need administrator access.

### Mac

Works on Macs with Apple silicon (M1 or later). Intel Macs aren't supported yet.

1. Download the file ending in `-mac-arm64.dmg`.
2. Open it and drag PFO to Applications.
3. Open PFO from Applications. If macOS blocks it, go to **System Settings › Privacy & Security**, scroll down, and click **Open Anyway**.

## Getting started

The first time you open PFO, you'll name your household, add its members and choose a password of at least 10 characters. A short tour then shows you around. You can also click **Try the demo** first to explore with made-up data.

From there:

1. Add your accounts, or bring in history from a spreadsheet with **Import**.
2. Use **Update balances** about once a month to record what each account holds or owes.
3. Set your goals for the year, and rank them by what matters most.

## Updating

- **Windows:** PFO updates itself. When a new version is ready, it asks whether to restart now or later. If you choose later, the update installs the next time you quit.
- **Mac:** updates are by hand for now. Quit PFO with Cmd+Q, download the new `.dmg` from the [latest release](https://github.com/smithsam7/pfo-releases/releases/latest), and drag PFO to Applications again.

Your data carries over either way, and PFO saves a copy of it first if an update needs to change how it's stored. Once your data has been updated, an older version of PFO won't open it.

## Your data

Everything you enter stays in a file on your computer, and nobody else, including whoever made the app, can see it. Nothing about your household is sent anywhere. The only thing PFO fetches from the internet is the update check on Windows, which reads this repository's public release files.

- **Where it is:** `%APPDATA%\PFO` on Windows, and `~/Library/Application Support/PFO` on a Mac. **Settings › Your data** shows the exact path.
- **It isn't encrypted:** your PFO password guards the app, not the file. Turn on disk encryption (BitLocker on Windows, FileVault on a Mac) to protect it if your computer is lost or stolen. On Windows, an administrator of the computer may also be able to read the file.
- **Back it up:** there's no cloud copy, so if your computer is lost, your data goes with it. Use **Settings › Your data › Download backup** now and then, and keep the file somewhere private and off that computer. Backups aren't encrypted either.
- **Moving to a new computer:** install PFO there, finish setup, and use **Restore** in **Settings › Your data** with your backup. Your password becomes the one from the backup.

## If you need to

- **Forgot your password:** choose **Reset Password…** from the PFO menu on a Mac, or the File menu on Windows. Your data stays as it is.
- **Start over:** use **Delete everything** in **Settings › Your data**. It needs your password and permanently erases your household from this computer, along with the copies PFO kept. It can't be undone, and backups you've saved elsewhere aren't touched.

## Licence

PFO is free to install and use. It is not open source: all rights reserved.
