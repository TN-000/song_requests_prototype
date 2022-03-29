# song_requests_prototype

This is a simple song requests form that can add a track to your chosen Spotify playlist. It handles Spotify authentication as well as searching for and adding tracks to the correct playlist.

# Set-Up
Download this repository and start a local server. This can either be done with Python in the directory this project is stored in:
```
# If Python version is 3.X
python3 -m http.server
# If Python version is 2.X
python -m SimpleHTTPServer
```
Or you could start a server in Visual Studio Code using the 'Live Server' extension.

Make sure the port the server starts on matches the redirect URI in the code - this might need to be changed in the app.js file and in your Spotify Developer Dashboard

# Run
Open up index.html in the browser using the address that your local server is running on.
Follow the instructions from here.

# Disclaimer!
This is a very very simple prototype, there is not much validation or many functionalities implemented yet! :)
