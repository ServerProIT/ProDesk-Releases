# ProDesk — notices and source availability

ProDesk is a modified version of RustDesk, maintained for ServerPro.
Upstream: https://github.com/rustdesk/rustdesk
Base: RustDesk 1.5.0, commit fada664df7a294d1d1a9ca3e7cd3637069122f17.
Modifications dated 2026-10-21: ProDesk branding and icon, ServerPro footer,
editable server defaults, replacement-only masked key field, key-free settings
export, Windows x64 packaging, source and build documentation.
Modifications dated 2026-10-22: ProDesk 0.1.0 versioning, unattended deployment
and ProDesk updates, local folder address book with JSON import and export.

Copyright notices of RustDesk and its contributors are retained. The original
LICENCE file is unchanged: GNU Affero General Public License, version 3.
ProDesk modifications are distributed under the same AGPL-3.0 license.
Dependencies retain their respective licenses and notices.

Corresponding source, including the pinned hbb_common submodule and build
scripts, is supplied as ProDesk-0.1.0-source.tar.gz with the release.
Public releases and corresponding source: https://github.com/ServerProIT/ProDesk-Releases/releases
Development repository: https://github.com/ServerProIT/ProDesk
Every recipient of the binary must also receive access to the corresponding
source and this license. A private repository alone does not provide access to
recipients outside that repository; supply the source archive alongside the EXE
or provide an accessible source download. When deploying a modified networked
version, provide its users an accessible offer of the corresponding source in
accordance with AGPL section 13. Do not remove the source link or notices.

The embedded server Key is an Ed25519 public verification key, not a private
server key. It is visible in the corresponding source and can be extracted from
the binary. The interface hides it and does not export it; this is not encryption
or a guarantee of secrecy from the person operating the computer.

ProDesk is independently customized and is not an official RustDesk release.
The icon was supplied by the user and processed with ImageGen to make the outer
background transparent. RustDesk trademarks do not imply endorsement.
