<p align="center">
  <a href="https://sponsor.ajay.app"><img src="https://raw.githubusercontent.com/ajayyy/SponsorBlock/refs/heads/master/public/icons/LogoSponsorBlocker256px.png" alt="Logo"></img></a>

  <br/>
  <sub>Logo by <a href="https://github.com/munadikieh">@munadikieh</a></sub>
</p>

<h1 align="center">SponsorBlock Safari</h1>

[![License: GPL-v3](https://img.shields.io/badge/license-GPL_v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![GitHub Release](https://img.shields.io/github/v/release/danny900714/sponsorblock-safari)](https://github.com/danny900714/sponsorblock-safari/releases/latest)

Install [SponsorBlock](https://github.com/ajayyy/SponsorBlock) on macOS [**for free**](https://apps.apple.com/us/app/sponsorblock-for-youtube/id1573461917) without the hassle of building the extension manually for every update.

SponsorBlock is an open-source crowdsourced browser extension to skip sponsor segments in YouTube videos. Users submit when a sponsor happens from the extension, and the extension automatically skips sponsors it knows about. It also supports skipping other categories, such as intros, outros and reminders to subscribe.

## Installation

There are two ways to install the extension:

### Method 1: Homebrew (Recommended)

If you have installed [Homebrew](https://brew.sh), you can install SponsorBlock with:

```shell
brew install danny900714/tap/sponsorblock
```

### Method 2: Download manually from Latest GitHub Release

#### Download the extension

1. Go to the [latest release](https://github.com/danny900714/sponsorblock-safari/releases/latest) page.
2. Under **Assets**, click the file whose name ends in `.dmg` to download it.
3. Open the downloaded `.dmg` file from your **Downloads** folder.
4. In the window that appears, drag the **SponsorBlock for YouTube** icon onto the **Applications** folder.
5. Open **SponsorBlock for YouTube** from your **Applications** folder.

#### Opening SponsorBlock for the First Time

SponsorBlock isn't notarized by Apple, so the first time you open it, macOS shows a warning that the app can't be verified.
This is expected. Use **one** of the options below to allow it. You only need to do this once.

**Option 1: System Settings (no Terminal needed)**

1. Try to open SponsorBlock for YouTube once, then close the warning by clicking **Done**.
2. Open **System Settings** and go to **Privacy & Security**.
3. Scroll down to the **Security** section and click **Open Anyway** next to SponsorBlock for YouTube.
4. Click **Open Anyway** again in the pop-up, then enter your password or use Touch ID.

**Option 2: Terminal**

1. Open **Terminal**: press `⌘ Space`, type `Terminal`, and press Return.
2. Copy the command below, paste it into the Terminal window, and press Return:
   ```
   xattr -dr com.apple.quarantine '/Applications/SponsorBlock for YouTube.app'
   ```
3. Open SponsorBlock for YouTube from your **Applications** folder as usual.

## Enable SponsorBlock on Safari

The first time you install the Safari extension, you'll need to enable it and grant the required permissions.

1. Open SponsorBlock for YouTube from your **Applications** folder.
2. Click **Quit and Open Safari Settings...**.
3. Select the checkbox next to **SponsorBlock for YouTube**.
4. Open [YouTube™](https://youtube.com), then click the SponsorBlock icon in Safari toolbar.
5. Click **Always Allow on This Website**.

### License

This project is licensed under [GNU GPL v3](./LICENSE).
