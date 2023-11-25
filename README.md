# User_Authentification_Nodejs_JWT

### 유튜브 형님 조언..
If you're building your own authentication system, it's a really good idea to include a flag in your payloads, to indicate whether that token was generated by authenticating with user credentials, or by using a refresh token. You can use this flag to authorize sensitive operations, such as changing your password or making payments - so if the user didn't log in recently, you can prompt them to log in again for sensitive operations. I would say this is a must for most applications.