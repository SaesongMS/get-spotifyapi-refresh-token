# get-spotifyapi-refresh-token

Simple script to get a refresh token for the Spotify API.

## Usage
Paste your client ID and secret to the respective variables in the script.
Add redirect URI to the list of allowed redirect URIs in your Spotify developer dashboard.
Start your script with:
```
node server.js
```
Open your browser and navigate to:
```
localhost:3000/login
```
You will be redirected to the Spotify login page. After logging in, you will be redirected to the redirect URI you specified earlier. The refresh token will be displayed in the browser window.
