# Cyra

![Cyra](cyra.png)

A minimalist Windows desktop notch companion. Designed by Paim.

[Download latest release](https://github.com/Paim41/CyraInstaller/releases/latest) · [All releases and notes](https://github.com/Paim41/CyraInstaller/releases) · [Website source](https://github.com/Paim41/Cyra)

## Install
Download the versioned Cyra-Setup EXE from Releases, compare its SHA-256 with SHA256SUMS.txt, then run the setup wizard and follow its instructions. Launch Cyra after setup. The current release is unsigned.

Requires x64 Windows 10 build 17763 or later (including Windows 11) and .NET Framework 4.8. This minimum is configured, not a claim of testing every Windows version. Uninstall through Windows Settings > Apps > Cyra. User settings are preserved.

Word-to-PDF needs Microsoft Word. PDF-to-Word needs separately configured optional dependencies; consult the installed INSTALLATION.txt. Neither Word nor the optional Python environment is bundled.

This repository distributes compiled installers and notices. It does not contain the private Windows application source. EXEs belong in Releases, never Git history.

Cyra derives from Gili by Maulana, under MIT. The original license is preserved in LICENSE and in the installer. See THIRD-PARTY-NOTICES.txt and licenses/ for bundled dependencies. Branding and Cyra contributions are by Paim.

## Future releases
Build the current Windows source with its existing installer script, verify version/payload and tests, compute SHA-256, then publish a new stable vX.Y.Z release with Cyra-Setup-vX.Y.Z.exe and SHA256SUMS.txt. Do not replace an existing release with different bytes. The website resolves the latest stable release automatically; no website filename edit is required.
