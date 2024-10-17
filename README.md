# Spotify Playlist Recommendation

This plugin recommends a Spotify playlist based on user descriptions using the **Spotify Web API**.

## Playlist Personalization  
- Use Spotify’s **recommendation endpoint** to generate tailored playlists.
- Example: Create playlists based on **mood, genre, or number of songs**.

👉 **Get started with the Spotify Web API:**  
[Spotify API Documentation](https://developer.spotify.com/documentation/web-api)

🔑 **Set up Your Spotify App and Authenticate with OAuth 2.0:**  
[Create a Spotify App](https://developer.spotify.com/dashboard/applications)  
- **Spotify's API requires OAuth 2.0 for access.** Learn more: [Spotify OAuth Guide](https://developer.spotify.com/documentation/general/guides/authorization)  
- **Update your app credentials in the plugin's user settings:**  
  - **Client ID:** `XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX`  
  - **Client Secret:** Save this securely, as it will only be shown once.

## ❗ Important Notes

### Rate Limits  
In **Development Mode**, your app can onboard up to 25 users and access all OAuth scopes. To unlock higher rate limits, apply for **Extended Quota Mode**, where Spotify will review your app for compliance. Learn more: [Spotify Rate Limits](https://developer.spotify.com/documentation/web-api/concepts/rate-limits)

## Example Usage  
As a coffee shop manager, I’d like to ask AI to suggest a song list for today:  
> Create a Spotify playlist with about 20 songs for my coffee shop. Today is a great day, so I’d like the playlist to help everyone stay calm and focused on work.
