# lyrics-finder
Command line lyrics finder

## Requirement
>python3, pip3

## Installation

lyrics-finder is compatible with Linux
```
git clone https://github.com/sumankhdka/lyrics-finder
cd lyrics-finder
pip3 install -r requirements.txt --user
```
## Basic usage
```
./lyrics-finder "artist" "song_title"
```


***
Download [mps-youtube](https://github.com/mps-youtube/mps-youtube)
Commandline youtube music player that works with lyrics-finder
```
git clone https://github.com/mps-youtube/mps-youtube.git
cd mps-youtube
pip3 install --user . 
```
You'll also need [youtube-dl](https://github.com/ytdl-org/youtube-dl) and mplayer to run mpsyt(mps-youtube)

```
pip3 install --user youtube-dl
```

If mplayer is not installed, check your linux distribution method for installing mplayer
***

Play youtube song with mpsyt (mps-youtube)

**Running mpsyt**

Example
```
mpsyt /cranberries
```


Check [mps-youtube](https://github.com/mps-youtube/mps-youtube) for more information

If you have problem playing in mpsyt try using [mpv](https://mpv.io/installation/)

Type this in mpsyt 
```
set player mpv
```

***
**Find song playing in mpsyt**

Make sure you are in lyrics-finder folder

```
./finder.sh
```



If 'finder' can find your song title and artist then run this to find lyrics for playing song
```
./lyrics-finder
```

