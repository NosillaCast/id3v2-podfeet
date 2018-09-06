# id3v2-podfeet
An ID3 Editor for Podcasters

This script will add a set of ID3 tags and album artwork to your podcast file according to theid3.org specs. I have tested it with audio but not video files.  Running of the script requires the following libraries:

* id3v2 from Myer's Carpenter at https://github.com/myers/id3v2
* ffmpeg


The script will add the following ID3 tags to your podcast file:

* Episode title with the name of the input file without extension (e.g. input of myEpisode.mp3 will have a title of myEpisode)
* Website url
* Podcaster's name
* Podcast title
* Year
* Copyright
* Genre
* Album art if you supply it

