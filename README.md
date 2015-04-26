# picard-scripting
MusicBrainz Picard is a music tagger (ID3 etc) that uses the MusicBrainz database as a source of information.
You provide Picard with your MP3s, FLACs, M4As etc, it will recognize the music with acoustic fingerprinting, find the correspondent artists, albums and tracks in the MusicBrainz online database and use this information to tag (ID3 etc) your files.

Picard can be scripted and these are my personal configurations. They do the following:

* Rename the files according to the tags in a coherent ARTIST/ALBUM_WITH_YEAR/TRACK filesystem structure.
* Change non-filesystem-friendly chars on filenames into filesystem-friendly ones using Unicode. For example: #➡♯, :➡∶, /➡／, *➡✱ etc
* Correctly handle release date versus original release date, number of discs etc
