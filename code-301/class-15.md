# Class 15 Summary
## Code 301 - Intermediate Software Development

> These topics relates because 0auth lets you use cool apps and websites without giving away your private passwords, keeping your information safe while still letting you enjoy online services.

### What is 0Auth
1. What is OAuth?
> 0Auth allows websites and services to share assets among users. OAuth lets you grant the app limited access without sharing those secret details. It's like giving a special, temporary key to the app that only works for the things you're comfortable with. This way, your private information stays safe while still letting the app do what it needs to do.
2. Give an example of what using OAuth would look like.
> When you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
> 1. You Visit the Pokémon Website - You go to the Pokémon trading and battling website and see an option to log in using your Google account.
> 2. Clicking the Google Login - Instead of creating a new account or entering your existing username and password, you click on the "Login with Google" button.
> 3. Redirect to Google - Clicking this button redirects you to Google's official login page. You log in with your Google account credentials.
> 4. Authorization Request - After logging in, Google asks you if you want to allow the Pokémon website to access some information from your Google account. The website specifies that it needs your email address to create your account and a unique ID to identify you.
> 5. Granting Limited Access - If you agree, Google generates a special token that represents your permission. This token is limited in scope, allowing the Pokémon website only to access the email address and unique ID, nothing else.
> 6. Returning to the Pokémon Website - After granting permission, you're sent back to the Pokémon website with the special token.
> 7. Access Granted - The Pokémon website receives the token and understands that it can access your email address and unique ID from your Google account.
> 8. Account Creation -  The website uses this information to create your account and assigns the unique ID to it. You're now a registered user without needing to share your Google password with the Pokémon website.
4. What is OpenID?
> While 0auth is about authorization, OpenID is about authentication. As pithily from StackOverflow mentioned, "OpenID is for humans logging into machines while 0auth is for machines logging into machines on behalf of humans."

### Authorization and Authentication flows
1. What is the difference between authorization and authentication?
> Authorization decides what you can do once your identity is confirmed.
> Authentication verifies who you are.
2. What is Authorization Code Flow?
> Authorization Code Flow is an OAuth 2.0 authentication process where a user is redirected to a third-party service to log in, and upon successful login, the service provides an authorization code to the requesting application. The application then exchanges this code for an access token, allowing it to securely access the user's resources.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
> Authorization Code Flow with Proof Key for Code Exchange (PKCE) is an enhanced OAuth 2.0 authentication process designed for better security, often used in mobile and native applications. It ensures that even if the authorization code is intercepted, an additional secret ("code verifier") is required for token exchange, adding an extra layer of protection against certain attacks.
4. What is Implicit Flow with Form Post?
> Implicit Flow with Form Post is an OAuth 2.0 authentication method designed for client-side web applications. It involves obtaining access tokens directly through the browser using a hidden form post, providing a secure way to handle authentication without exposing tokens in the browser's URL.
5. What is Client Credentials Flow?
> Client Credentials Flow is an OAuth 2.0 authentication process used by applications that need to access resources on their own behalf rather than on behalf of a user. It involves the application directly exchanging its client credentials (client ID and client secret) for an access token, granting it access to protected resources.
6. What is Device Authorization Flow?
> Device Authorization Flow is an OAuth 2.0 authentication mechanism designed for devices with limited input capabilities, such as smart TVs or IoT devices. The flow allows users to authorize these devices by displaying a user code and a URL on the device's screen, which the user can input on a separate device to complete the authentication process and grant access.
7. What is Resource Owner Password Flow?
> Resource Owner Password Flow is an OAuth 2.0 authentication method where the user's credentials (username and password) are directly exchanged for an access token, typically used in trusted applications like first-party mobile apps. However, this flow is considered less secure and less recommended compared to other OAuth flows that avoid exposing user credentials to the client application.

### Things I want to learn more about.
> I want to learn more about implementing authentication/authorization functionality in my web applications.


###### I also utilized ChatGPT with these questions.