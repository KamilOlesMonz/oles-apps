# OLEs Apps Repository Template

This repository stores update manifests for every OLEs application.

Update process:
1. Build a new installer.
2. Upload it to a GitHub Release.
3. Update the matching manifest (version, download URL, SHA-256).
4. Commit and push.
5. OLEs Hub will detect and install the update automatically.
