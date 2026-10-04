# MediaViewer

A fast, minimal photo and video library browser for Windows 11.

- SQLite-cataloged libraries with automatic background rescans
- Virtualized thumbnail grid with Windows shell thumbnails and hover-to-play previews
- Tagging, favorites, 0-10 ratings, view names, and on-device face recognition
- Filter-expression bar (WHERE-style queries over name, tag, face, rating, favorite, kind)
- Go to folder, plus batch Copy / Move / Delete for multi-selections with per-file skip reasons

## Download

Grab `MediaViewer-<version>.zip` from the [Releases](../../releases) page.

## Running

Unzip anywhere and run `MediaViewer.exe` (Windows 10 or 11, 64-bit). No installer.
Face-recognition models ship inside the zip. Settings and catalogs live under
`%LocalAppData%\MediaViewer`. No network access, no telemetry.

## Third-party components

MediaViewer ships SQLite (public domain), ONNX Runtime and DirectML (MIT),
the Windows App SDK runtime, the OpenCV Zoo YuNet detection model (Apache 2.0),
and an AdaFace IR-50 recognition model (MIT). Full notices: THIRD-PARTY-NOTICES.txt
inside the zip.

## Status

Source is not published in this repository; it hosts release binaries only.
All rights reserved.
