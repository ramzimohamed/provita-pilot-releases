# ProVita pilot downloads

LOCAL UPDATE TEST PASSED (2026-09-24): the real 0.1.3-to-0.1.4 update was downloaded, verified and installed on our Mac, followed by restart, re-login and a synthetic contact list/detail check. The app shows version 0.1.4. Updates remain explicitly initiated and confirmed by the user. Installation on the recipient's own Mac remains untested. This is a limited synthetic-data preview, not approval for production use.

This repository contains signed ProVita pilot installers, update archives and
public update metadata only. ERP source code, credentials, internal evidence,
backups and customer data are not published here.

Version 0.1.4 is provided for Apple Silicon Macs running macOS 14 or later.
The app and DMG are signed and notarized. See INSTALLATION.md and BYTE-PINS.json
for installation guidance and exact checksums.

This UI maintenance release is based on the shipped 0.1.3. It removes the visible
“Noch nicht verfügbar” navigation heading, extends the sidebar to the available
height and adjusts content/list spacing. Unavailable modules remain disabled;
the feature set and read-only limits are unchanged.

An available download is not by itself approval for production use or processing
real customer data. This is the existing pilot feature set, not the complete ERP.
The real local 0.1.3-to-0.1.4 update was observed, not inferred from the presence
of these files. Updates are explicitly initiated in the application; they are
not installed unattended. The separate synthetic test environment has no fixed
shutdown deadline as of 2026-09-24.
Database, API and tunnel autostart were verified after a controlled restart of
the ProVita VM, followed by a successful in-app session and contact-detail check.
Host boot autostart is configured; the shared host was not rebooted. This is not
an uptime guarantee or approval for real customer data.
