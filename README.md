# QApostman
postman scripts for basic api calls
//written by StevenOn

To run the basic postman calls, both the environment file and collection need to be imported into postman. 
1. Please update the client_key and client_secret to your credentials. 
2. Please run 'createAccessToken' before running any other calls. 
    - This will create an access token and save it into the environment variable 'access_token' 
    - All subsequent calls will be able to use this token for auth
3. Run as needed 
