KDE_puush
=========

bash wrapper for puush and KDE

Installation:

1. Set the variable PUUSH_API_KEY in /usr/bin/KDE_puush or with 'export PUUSH_API_KEY=\"apiKeyHere\"

2. Add keyboard shortcut that calls "KDE_puush"

3. Optionally include Scrot parameters behind command. Specifically "-s" to switch from full screenshot to interactive area/current window. Parameters must be in quotationmarks, see scrot -h for options.

example: KDE_puush "-s"

Requirements:
Scrot,
kdebase-kdialog
