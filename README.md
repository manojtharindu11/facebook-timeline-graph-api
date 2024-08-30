# Facebook-timeline

This project is a simple Facebook-like feed that displays the latest posts from a user's Facebook timeline. The feed is styled to resemble a typical Facebook feed and dynamically fetches and displays posts using the Facebook Graph API.

## Facebook Feed Integration

The feed is powered by the Facebook Graph API. The `facebookFeed.js` script fetches data from your Facebook timeline and dynamically updates the feed with the retrieved posts. To use this functionality, you must obtain a Facebook access token and replace the `accessToken` variable in `facebookFeed.js`.

### Steps to Obtain a Facebook Access Token:

1. Go to the [Facebook Developer Portal](https://developers.facebook.com/).
2. Create a new app or use an existing one.
3. Navigate to the "Access Token Tool" in the "Tools" section.
4. Generate an access token with the necessary permissions (`user_posts`).
5. Copy the generated access token and replace the `accessToken` variable in `facebookFeed.js`.
