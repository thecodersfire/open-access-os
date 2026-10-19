# Built-in features for open-access-os

Purpose: accessibility workflows

1. **organize project files** — run open-access-os-workspace. It creates ~/Documents/open-access-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run open-access-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/open-access-os-session-plans/.
3. **check task readiness** — run open-access-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/open-access-os-workspace features/open-access-os-plan features/open-access-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for accessibility workflows:

1. **Zotero** — org.zotero.Zotero
2. **Anki** — net.ankiweb.Anki
3. **Foliate** — com.github.johnfactotum.Foliate

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for accessibility workflows:

1. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
2. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
3. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
4. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
5. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
6. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
7. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
8. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
9. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
10. **GNOME Weather** — check local weather conditions (org.gnome.Weather)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
