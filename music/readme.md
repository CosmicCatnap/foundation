# Music

## Selection

Music is one of the more difficult subjets to determine selection because so much of what makes music wonderful is personal and subjective. The loose goal of the music component of the foundation archive is to select music which displayed as wide as possible the diversity of musical tastes while also keeping the selection of items of low quantity and high quality. Even with conservative storage conventions music can become a storage intensive media and as such the archive will only select particular albums from artists.

## Structure and Metadata

The structure should be the name of the artist and then the album name in the root of this directory for example

artist/album/{01-songname.aac, 02-songname.aac, 03-songname.aac}

It is recommended that a text only export of the artists wikipedia page should be stored in a file named readme.md in the folder named after the same artist and the wikipedia for the album name be in the readme.md alongside the album songs.

## Formatting

Ideally music would be stored in FLAC or WAV formats directly recorded from vinyl but the process of doing this is difficult and cumbersome which is not the goal of the foundation archive, instead it is best to provide the lowest bar to entry for everyone who can contribute. Considering this, we will strive for formatting that should be easy to achive from a CD copy of an album with easily available software.

* 44.1kHz
* 16 Bits
* 256 kbps
* AAC encoding

## Naming Conventions

Keeping in theme with other subjects in the archive, filenames should have the following conditions

* lower case
* no special characters
* spaces(' ') replaced with underscore('_')

One exception to this rule is song names which should not be modified from their album original strings, as song names are a type of artistic choice and should be preserved as the artist intended. Archivists are encouraged to use `"` as the only optional modification in order to avoid human error caused by dealing with escape charters or special characters.