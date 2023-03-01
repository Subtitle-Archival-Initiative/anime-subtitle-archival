# Anime Subtitle Archival

This repository serves as an archive of anime subtitles (both official and fan-made).

It contains subtitle files and attachments necessary to properly display them (such as fonts).
This does NOT include video and/or audio files.

Are your subtitles, fonts, or other properties found within the repo and would you like us to remove them?
Please leave an issue detailing the exact paths to files we must remove,
as well as a method through which we can identify you as the rightful owner.

## How are files separated?

Files are separated by anime, based on [aniDB]. aniDB IDs are included at the end of each directory.
This should make finding all the subtitles related to specific anime and seasons a lot easier.

Afterwards, they're split by group tag.
In the event of an untagged release, it will be given a special directory inside of an "Untagged" directory,
unless they're official subtitles, in which case name of the publisher or "Official" will be used instead.

The subtitles are then split up by episode number and versioning (if applicable).
Should a file exceed 100MB (GitHub limitation), it will be split into however many parts are necessary.

## Are the files modified?

In most ideal scenarios, they are not.
They should reflect the original subtitles as much as reasonably possible.
However, changes may be made to ensure it still renders correctly with modern subtitle renders.

Latest available revision of the subtitles will be used if available,
otherwise any that could be acquired at the time of upload.

## Contributions

Want to contribute? Please leave an [Issue] or create a [Pull Request]!
Please ensure you follow the relevant template or your contribution will automatically be denied.

Please note that we only accept the following file contributions:

* Text-based subtitle files (*ASS*, *SRT*), ***NOT*** image-based (*PGS*)
* Fonts (*TFF*, *OTF*, *TTC*), but only those necessary for the specific subtitle to display properly
* README Markdown files including information about the subtitles (such as the people who worked on it)
* Files *strictly necessary* to ensure correct subtitle rendering

As of the time of writing, we do ***NOT*** accept the following contributions:

* Non-English/non-Japanese subtitles
* Non-anime subtitles


[aniDB]: https://anidb.net/

[Issue]: https://github.com/LightArrowsEXE/anime-subtitle-archival/issues
[Pull Request]: https://github.com/LightArrowsEXE/anime-subtitle-archival/pulls
