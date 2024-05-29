Here's a summary of the files and their functionality:

index.html
This is the main page where users enter their credentials to authenticate with Genesys Cloud. It contains form fields for Client ID, Redirect URI, and Genesys Cloud Environment, with basic validation.

auth.html
This page handles the OAuth redirection, extracting the access token from the URL and redirecting to success.html with the token as a query parameter.

success.html
This page displays a menu with buttons for different Genesys Cloud configuration utilities. It includes a search bar for real-time filtering of the button list and a special button for navigating to prompts.html.

error.html
This page is displayed if there is an error during authentication. It shows an error message and redirects back to index.html after 5 seconds.

prompts.html
This page allows users to download media files and CSV data related to Genesys prompts. It includes a popup for importing settings and displays the status of downloads in a textarea.
