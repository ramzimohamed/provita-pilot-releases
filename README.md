# ProVita pilot downloads

LOCAL UPDATE RETEST PASSED (2026-09-24): the real 0.1.2-to-0.1.3 update installed and automatically restarted. Re-login, synthetic contact list/detail and the visible 0.1.3 / current-version check succeeded. The feed points to the newly signed corrected archive under repack-2e9130af. The signed application and DMG are unchanged. Do not use the historical archive at /0.1.3/aarch64/. Installation on the recipient's own Mac remains untested. This is a limited synthetic-data preview, not approval for production use.

This repository contains signed ProVita pilot installers, update archives and
public update metadata only. ERP source code, credentials, internal evidence,
backups and customer data are not published here.

Version 0.1.3 is provided for Apple Silicon Macs running macOS 14 or later.
The original signed and notarized app and DMG are unchanged. See INSTALLATION.md
and BYTE-PINS.json for installation guidance and exact checksums.

An available download is not by itself approval for production use or processing
real customer data. This is the existing pilot feature set, not the complete ERP.
The real local 0.1.2-to-0.1.3 update was observed, not inferred from the presence
of these files. Updates are explicitly initiated in the application. The separate
synthetic test environment has no fixed shutdown deadline as of 2026-09-24.
Database, API and tunnel autostart were verified after a controlled restart of
the ProVita VM, followed by a successful in-app session and contact-detail check.
Host boot autostart is configured; the shared host was not rebooted. This is not
an uptime guarantee or approval for real customer data.
