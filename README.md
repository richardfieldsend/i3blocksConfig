# i3blocksConfig
i3blocks configuration for home and work

## February 2020.

I have moved the i3blocks configuration into a Git repository, and
modified a few settings.

* Removed the entry for the volume (without headphones the system is
  muted, and the volume displayed was not the correct one anyway).

* Modified the time/date entry so it has the time, then the date, and
  doesn't display the seconds (this only changed every 5 seconds, so
  was jarring anyway).

* Added an entry in the configuration to display the artist and track
  information when music is being played via Spotify. The function
  uses a script and an entry in the configuration file. This is
  outlined here:
  https://github.com/firatakandere/i3blocks-spotify. The script needs
  to be made executable.
