# Trakt-Auth-Helper
### Trakt OAuth Authentication
Manual version of [https://github.com/PierreDurrr/Trakt-Auth-Helper-Docker](https://github.com/PierreDurrr/Trakt-Auth-Helper-Docker)

## Overview:
This Python script facilitates OAuth authentication with the Trakt.tv platform. It guides users through the authentication process, prompting them to input their Trakt client ID, client secret, and authorization code obtained from Trakt's authorization page. Upon successful authentication, the script retrieves the access token from Trakt.tv, enabling users to interact securely with Trakt's API.

## Features:
1. **Trakt OAuth Authentication**: Users can authenticate their applications with the Trakt.tv platform using their client ID, client secret, and authorization code.
2. **Interactive User Experience**: The script provides a user-friendly experience with interactive prompts guiding users through the authentication steps.
3. **Access Token Retrieval**: Upon successful authentication, the script retrieves the access token, which allows users to access Trakt's API securely.
4. **Error Handling**: The script handles authentication failures gracefully, providing feedback to users if credentials are incorrect or if other errors occur during the authentication process.

## Dependencies:
- requests: For making HTTP requests during the authentication process.

## How to Use:
1. Run the script.
2. Enter your Trakt client ID and client secret when prompted.
3. Visit the provided authorization URL and input the authorization code obtained from Trakt's authorization page.
4. The script will exchange the authorization code for an access token. Upon successful authentication, it will display the access token.
