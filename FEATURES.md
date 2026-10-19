# Built-in features for waveform-works-os

Purpose: music recording, audio editing, and podcast production

1. **prepare a creative project** — run waveform-works-os-workspace. It creates ~/Documents/waveform-works-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run waveform-works-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/waveform-works-os-session-plans/.
3. **check project and export readiness** — run waveform-works-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/waveform-works-os-workspace features/waveform-works-os-plan features/waveform-works-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for music recording, audio editing, and podcast production:

1. **Mixxx** — org.mixxx.Mixxx
2. **GIMP** — org.gimp.GIMP
3. **Inkscape** — org.inkscape.Inkscape

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for music recording, audio editing, and podcast production:

1. **Kdenlive** — edit video timelines (org.kde.kdenlive)
2. **Blender** — create 3D assets and animations (org.blender.Blender)
3. **GNOME Sound Recorder** — capture voice and field notes (org.gnome.SoundRecorder)
4. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
5. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
8. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
2. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
3. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
4. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
5. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
6. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
7. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
8. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
9. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
10. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
11. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
12. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
13. **GNOME Papers** (org.gnome.Papers) — read project and reference PDFs.
14. **GNOME Clocks** (org.gnome.clocks) — time work sessions and events.
15. **GNOME Contacts** (org.gnome.Contacts) — organize partner and team contacts.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.

## Fifteen further purpose-specific preinstalled applications

This second batch adds another set of apps selected for this setup’s purpose. They are installed from Flathub by the setup scripts.

1. **Kwave** (org.kde.kwave) — record and edit audio waveforms with basic filters and analysis.
2. **EasyEffects** (com.github.wwmm.easyeffects) — shape microphone and output audio with PipeWire effects.
3. **Elisa** (org.kde.elisa) — organize and play local music libraries.
4. **Kid3** (org.kde.kid3) — edit and normalize audio file tags and album metadata.
5. **Kamoso** (org.kde.kamoso) — capture webcam photos and short video clips.
6. **Minuet** (org.kde.minuet) — practice music theory and ear-training exercises.
7. **Okular** (org.kde.okular) — read, bookmark, and annotate technical drawings, reading lists, and reference PDFs.
8. **Dolphin** (org.kde.dolphin) — organize project assets and inspect folders.
9. **Ark** (org.kde.ark) — open and create common project archive files.
10. **Filelight** (org.kde.filelight) — find large folders and reclaim disk space.
11. **Warehouse** (io.github.flattool.Warehouse) — review installed Flatpaks, manage versions, and clean app data.
12. **Meld** (org.gnome.meld) — compare and merge source files, folders, and Git changes.
13. **Kate** (org.kde.kate) — edit configuration, code, notes, and structured project files.
14. **Konsole** (org.kde.konsole) — run shell commands and inspect development or system tasks.
15. **KCalc** (org.kde.kcalc) — run scientific and unit calculations for coursework or technical work.

Game frontends do not include proprietary game data; add only games or files you are allowed to use.

## Blender included in every setup

Blender (org.blender.Blender) is included in every setup for 3D modeling, animation, rendering, and video editing. Installers fetch it from Flathub; Blender’s own license and terms apply.

## Fifteen additional purpose-specific applications

The setup adds these Flathub applications for music recording, audio editing, and podcast production. Applications are fetched from Flathub by the setup script; each app keeps its own licensing and terms.

1. **Shotcut** (org.shotcut.Shotcut) — Edit multitrack video with filters, transitions, and titles.
2. **HandBrake** (fr.handbrake.ghb) — Transcode video files to common formats and presets.
3. **OpenShot** (org.openshot.OpenShot) — Assemble video clips on a multitrack timeline.
4. **Glaxnimate** (org.kde.glaxnimate) — Create vector animations, motion graphics, and animated SVG assets.
5. **Subtitle Composer** (org.kde.subtitlecomposer) — Create and synchronize captions for video projects.
6. **KPhotoAlbum** (org.kde.kphotoalbum) — Tag and organize large photo collections.
7. **Loupe** (org.gnome.Loupe) — View images and make simple crop, rotate, or flip edits.
8. **Kasts** (org.kde.kasts) — Subscribe to podcasts and manage playback queues.
9. **Jellyfin Desktop** (org.jellyfin.JellyfinDesktop) — Browse and play personal media from a configured Jellyfin server.
10. **digiKam** (org.kde.digikam) — Organize and annotate large photo libraries.
11. **Shotwell** (org.gnome.Shotwell) — Import, tag, and browse photo collections.
12. **RawTherapee** (com.rawtherapee.RawTherapee) — Develop RAW photographs with non-destructive controls.
13. **Gwenview** (org.kde.gwenview) — Review and make basic edits to image files.
14. **KolourPaint** (org.kde.kolourpaint) — Make quick annotations and simple raster image edits.
15. **Krita** (org.kde.krita) — Paint and illustrate with a brush-based workflow.
