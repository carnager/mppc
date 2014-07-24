# mppc - a mpc clone written in python-mpd2

mppc aims to be an almost exact clone of mpc using python-mpd2

# But why?
Because mpc depends on libmpdclient, which in turn is missing some of the newer features of the mpd protocol
python-mpd2 is the only up-to-date client library out there.

# So what advantages does it give me?
By now just a few:
* Possiblity to use all values of tracks, not only the tags associated with it
  (e.g. `mppc search album "Dirty" --format '{track} {Title} - Last Modified: {last-modified}`)
* Possiblity to format the output of search and find options.
* Possiblity to format the output of listall 
* readcomments support
