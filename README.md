# DustSol (beta)

DustSol is a Lightroom Classic plug-in that finds dust, hairs and scratches on
film scans, shows you every mark, and removes only what you approve. Repairs
keep the film grain, your originals are never changed, and everything runs on
your Mac.

Website: https://dustsol.pages.dev

This repository hosts the beta downloads only.

## Download

Get the latest installer from [Releases](../../releases/latest):

- `DustSol-<version>-beta.pkg`: installer (recommended)
- `DustSol-<version>-beta.zip`: the plug-in folder, to install by hand
- `DustSol-<version>-beta.sha256`: checksums

## Requirements

- A Mac with Apple silicon (M1 or later)
- macOS 14 Sonoma or later
- Lightroom Classic

## Install

1. Quit Lightroom Classic.
2. Open the `.pkg`. The beta is not yet signed with an Apple Developer ID, so
   macOS asks you to confirm it once: if it says the installer can't be
   opened, go to System Settings > Privacy & Security and click
   "Open Anyway".
3. Start Lightroom Classic. DustSol appears under Library > Plug-in Extras.

The full guide, including installing by hand and uninstalling, ships with the
plug-in as `INSTALL.txt`.

## Feedback

Sign up on the [website](https://dustsol.pages.dev) to get the download, the
feedback form and the address for questions and bug reports. The same address
is in `INSTALL.txt` inside the plug-in.

To show the marks DustSol got wrong, choose File > Export Feedback... in the
DustSol window. It saves small crops around the marks and your keep/remove
choices to a folder you pick; zip it and email it to us. Nothing is sent
automatically. You can also open an issue in this repository.

## Credits

DustSol's models were trained on "Authentically damaged & manually restored
film scans" and "Simulating analogue film damage to analyse and improve
artefact restoration on high-resolution scans" by D. Ivanova, J. Williamson,
P. Henderson (scans by d@analog.cafe), CC BY 4.0. The detection model builds on
DINOv2 by Meta AI (Apache License 2.0). DustSol includes OpenCV, KleidiCV,
Carotene and libtiff; their licences are in `THIRD-PARTY-NOTICES.txt` inside
the plug-in.

Lightroom and Lightroom Classic are trademarks of Adobe. DustSol is not
affiliated with Adobe.
