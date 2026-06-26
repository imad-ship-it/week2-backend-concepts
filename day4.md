day 4 learnings

authentications and why apis need it:
authenatication means to verify who the user is and the apis need it to protext the data of the user

sessions and tokens:
in sessions server remembers u and save sessions in the server like cookies in web
but in tokens the server doesnt remember you it just gives u a token and the client uses that token with each request to authenticate and jwt is alsa a form of token

jwt and its 3 parts:
jwt tokens are used to verify the user and also to secure the users data
header 
header is for information about the token like its type algorithm like that
payload 
payload is for information about the user like user id username email and all the information about the user and also the expiration time of the token
signature 
signature is for verifying that the token is not tampered with

access token vs refresh token:
access token is short lived and this is the main token the benifit of this short lived token is that even if a hacker enters he wont be able to damage for long time
refresh token is long lived this is the token which is used to get a new access token and it is stored in the server when access token expires the user sends this and gets a new token

isauthenticated vs allowany:
isAuthenticated allows only the request with valid jwt token on the other hand allowany allows any user to access the api

request.user and how drf sets it automatically:
request.user stores the data of the user who sends the request and  it is set automatically with the data of the user when the token is validated

filter nby request.user
it is used so that the user can access only his own tasks not the tasks of other users as well

also create.user is used so that when the user is saved its password is hashed 