**Using K-Means clustering on a spotify playlist**

Based on the code from :

https://medium.com/web-mining-is688-spring-2021/categorizing-music-using-k-means-clustering-b31f951c76d8

https://github.com/sejaldua/music-clustering/tree/master

For Information on Setting up your credentials for Spotify Web API, you can visit: 

https://developer.spotify.com/

***Quick-guide***

1) You can watch this short 2-minute instruction video on retrieving the various credentials required for this particular notebook:

https://youtu.be/P4BXtLPnpqY

2) After entering all the necessary credentials in the notebook and making the API call from your local machine, what should happen is:

- Spotipy opens a browser and connects to the authorisation service.
- The authorisation service redirects your browser to http://localhost?code=...
- Spotipy shows a prompt: "Enter the URL you were redirected to:"
- You copy the entire URL from your browser address bar and paste it into the console window python is running in.

You only need to do it the first time you request a new type of access, spotipy will cache the responses.

3) The list of audio features that can be retrieved from Spotify's web API can be found here:

https://developer.spotify.com/documentation/web-api/reference/get-audio-features
