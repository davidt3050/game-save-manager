# game-save-manager: Project Goals

## Project Summary
game-save-manager is a lightweight & locally-run video game save file manager supporting save file swapping & backups.

## Motivation
Managing video game save files can be a pain, especially when some games hide them in obscure places,
only support a couple active saves at a time, and don't perform any automatic save backups in case anything goes wrong.
This project seeks to solve this issue by providing gamers an easy-to-use interface that allows them to easily find save files for specific games,
deactivate saves to support unlimited save files in all games, and enable automatic backups with customizeable intervals so file corruption becomes a
minor hiccup instead of a catastrophe.
This project will also expose all of its features via a command-line application for users who prefer working with terminals or want to write scripts
that interact with this project.

This project is also intended to help me with C++ and systems programming, project management, and overall coding confidence.

## Core Features
- A native, clean, and easy-to-use GUI that allows users to access all features.
- A well-documented CLI that allows users to access all features.
- Native support for Linux and Windows 10/11.
- Automatic game & save file detection by frequently scanning common locations for save files.
- Support for manually adding games & save file locations that automatic detection missed.
- Allow save file swapping & activating/deactivating by moving save files between a configurable location and the normal save file location.
- Automatic & configurable save file backups to a configurable local or mounted cloud location.
- Easy save file reversion to an existing backup that also saves the beginning state as a new backup.
- Deletion of save files to system trash.

## Stretch Goals
- Add folders for the automatic game & save file detection to scan.
- Remove/exclude games from the manager; users can choose to preserve files or not.
- Automatic syncing between devices using user's cloud storage with data loss prevention and data conflict management.
- macOS support.

## Non-Goals
- iOS/iPadOS, & Android support.
- Direct cloud storage integration (i.e., send data directly to Google Drive instead of through mounted storage).

## Success Criteria

## Constraints
- Core features should be complete by August 24, 2026.
- Linux & Windows 10/11 must have native support.
- Both GUI and CLI must have equal feature support.
- Code must be mostly written in C++.
- Code must be built with CMake.
- Version control (Git) must be used.
- Commits must be made frequently.
- Features should be worked on in separate branches.
- GUI will use Qt6.
