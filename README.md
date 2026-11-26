# Vita Humilis updates

Download Windows x64 updates from [Releases](https://github.com/unmonitoredlemmings/vita-humilis-updates/releases/latest).

This repository hosts release packages, checksums and release notes for Vita Humilis. Application source code and personal books are not stored here.

## Install an update

Installed Windows x64 copies running 0.2.3 or later can use **Check for updates →
Download and install**. Vita Humilis downloads and verifies the package, saves
your current book, installs the new version and reopens it. You can cancel while
the package downloads or is being prepared. The previous installation is kept.

For a first installation, a portable copy, or an upgrade from 0.2.2 or earlier:

1. Save your work and close Vita Humilis.
2. Download the Windows setup ZIP from the latest release.
3. Extract the entire ZIP, keeping its installer and payload folders together.
4. Run `Install-Vita-Humilis.exe` and reopen Vita Humilis.

The installer replaces application files while preserving books and personal settings. Each release includes a SHA-256 checksum file for the download. Third-party notices are included in the package.

## Connect an older installation

Open **Check for updates**, enter `unmonitoredlemmings/vita-humilis-updates`, then choose **Save source & check**.

Version 0.2.2 bundles this update source. If an older saved setting overrides it, choose **Use publisher source & check**.

The app checks for newer stable releases. In-app installation uses the full
verified package and starts only when you choose **Download and install**.
Portable copies and other platforms retain the manual download option.

## Cloud pilot

Cloud sync is optional and enabled separately for each book. Email confirmation remains required. Until a production email provider is configured, signup delivery is limited to addresses on the Vita Humilis Supabase organization team. Offline writing remains available.
