# OrchardTail downloads

OrchardTail 0.1.1 is an early Windows x64 preview: four separate desktop applications featuring Apri, the red panda companion.

## Get started

1. Download [OrchardTail Hub for Windows](https://github.com/rickyboyy89-gif/orchardtail-downloads/releases/download/v0.1.1/OrchardTail-hub-0.1.1-win32-x64.zip).
2. Extract the entire ZIP into its own folder, then run `OrchardTail Hub.exe`. Keep the files beside the EXE together.
3. Hub checks for updates automatically. Use **Update apps** to download Floor Planner, Charts and Scribe. No GitHub login is needed.

[All release downloads and checksums](https://github.com/rickyboyy89-gif/orchardtail-downloads/releases/tag/v0.1.1) are available if you prefer individual portable app bundles.

## The apps

- **Floor Planner:** Residential and Industrial project paths, room/wall drawing, room detection, photos, editable grid scale and dimensions, illustrated furniture, network/electrical/plumbing overlays, searchable libraries, labeled devices, legends and schedules. SVG/PDF exports. Native `.otplan` projects.
- **Charts:** Editable connected diagrams, native `.otflow` projects and SVG/PDF export.
- **Scribe:** Type naturally; local rules sort tasks, decisions, questions, risks and key details. Native `.otnote` projects and Markdown export.
- **Hub:** Separate app launching and signed, verified updates. Running editors are left open; pending updates install after closing. Close and reopen Hub to finish its own update.

## Preview scope

This is an initial preview, with approximate editable furniture footprints and original equipment markers rather than a complete certified schematic-symbol standard library. It does not perform engineering calculations or code compliance validation. Advanced CAD constraints, full legacy feature parity and multiple floors in one project remain in development. Windows Authenticode signing is not yet configured.

Update manifests are Ed25519 signed, and downloads are checked against SHA256, file size and safe archive paths. Keep the extracted Hub folder as your launcher. Projects live separately under your Windows user application-data folder, and saves retain a previous-save backup.

This public repository distributes binaries, signed update metadata and checksums. Application source is maintained privately. No work-suite source, user projects, or signing private keys are distributed here.
