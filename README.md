
# the following is a rough draft of the downloader implemented as a iOS shortcut


Ask for Text with Album name (takes input)
mkdir "Provided input" -- forms a text file as shown in left
SHELL EXECUTE cd/private/var/mobile/Containers/Data/Application/LOCATION/Documents : Text(from above)
yt-dlp -o "%(playlist_index)02d   %(title)s.m4a" Clipboard -f m4a --add-metadata --embed-thumbnail --no-playlist --  save as text
SHELL EXECUTE cd/private/var/mobile/Containers/Data/Application/LOCATION/Documents cd "Provided Input" "text saved above"
