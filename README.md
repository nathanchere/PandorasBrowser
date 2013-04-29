# Pandora's Browser

Old project imported from my personal SVN server to Google Code. No longer supported - feel free to take it and make something crazy.

Intended to mess with open WiFi hotspots at cafes etc. Could also be fun to leave running at work to catch out employers monitoring what everyone is doing but use at your own risk.

## Usage

Two modes: random and playback.

Random will visit random sites from a list. There are plenty of lists provided. File format is simple - one URL per line. Very simple though, won't allow you to log in to anything.
The most fun requires sites which may be of questionable morality and/or legality so are not provided here, however there is a list of links to some extremely questionable content collected from the darkest corners
of the internet which can be found at https://pastebin.com/gpLn32Bw

Playback does as it says, plays back browser activity from a recording. This works with a lot of sites however can't handle things like anti-forgery tokens so test it out for a particular site first before you get carried away.
Recordings at the moment can either be written manually (look at ./Examples folder) or by setting your browser's proxy to https://code.google.com/p/pandorasrecorder (not without its quirks though)