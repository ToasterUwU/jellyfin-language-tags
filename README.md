# jellyfin-language-tags

A small python script to add language tags based on the audio files using Jellyfin REST API

Dependencies:
- python (i used python 3 but may works on others?)
- requests python lib
- [Jellyfin REST API](https://api.jellyfin.org/)

## Run

1. Set the vars JELLYFIN_URL, USERNAME, PASSWORD (tested with admin user only)
2. Run
```sh
python add_language_tag.py
```

See the comments in the files for more details

Special thanks to this gist that helped https://gist.github.com/mcarlton00/f7bd7218828ed465ce0f309cebf9a247

Feel free to fork or PR if you feel it could be better.
