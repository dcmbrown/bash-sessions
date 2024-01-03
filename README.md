### *Bash Environment Sessions Addition*

This is a bash sessions tracker for users who regularly sudoed into, run multiple terminal sessions at once, or are root.

#### *USE*
Add the bash_sessions file to the home directory of the user to track history sessions of better as `.bash_sessions` (or where ever you may put extra config files for bash such as `.bash.d/` or `.dotenv/`.
Add this to your .bashrc, .bash_profile, or .profile after any system bash imports and any other HISTORY exports in order enable this.

      source ~/.bash_sessions

This will create a directory for sessions to be stored. Subsequent sessions will show up under 

`~/.bash_sessions.d/history_<username>-[pt]ty[n]`
