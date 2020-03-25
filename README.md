# FB Liked Music Spotify Playlist
This program takes the user's liked musical artists on Facebook and creates a Spotify playlist with one song per liked artist.
The program uses each artist's top 10 songs list and adds the song closest in date with the date the user liked that 
artist on Facebook.

Updates to come:
- Fix song selection when non-iso format dates are passed in. Currently, if non-iso formatted dates like '2012', are passed
in, the program uses today's date and thus, selects the most recent song from the artist's top 10 list.
- Implement a way to add more than 100 songs to Spotify playlist. Spotify can handle 100 song track URIs in one request, however,
the user may have over 100 liked artist's on Facebook.
