# Class 15 Summary
## Code 301 - Intermediate Software Development

> These topics relates because...

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
> 
2. What is Authorization Code Flow?
> 
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
> 
4. What is Implicit Flow with Form Post?
> 
5. What is Client Credentials Flow?
> 
6. What is Device Authorization Flow?
> 
7. What is Resource Owner Password Flow?
> 

### Things I want to learn more about.
> I want to learn more about implementing/building 0Auth to my web applications.


###### I also utilized ChatGPT with some of the questions.