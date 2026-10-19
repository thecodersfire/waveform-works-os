# Built-in features for waveform-works-os

Purpose: music recording, audio editing, and podcast production

1. **prepare a creative project** — run waveform-works-os-workspace. It creates ~/Documents/waveform-works-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run waveform-works-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/waveform-works-os-session-plans/.
3. **check project and export readiness** — run waveform-works-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/waveform-works-os-workspace features/waveform-works-os-plan features/waveform-works-os-check "$HOME/.local/bin/"
