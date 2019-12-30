# file-repository
to get a token to test our application
Go to this uri in your nav:

https://{your-octa-base-uri}.okta.com/oauth2/default/v1/authorize?client_id={your-spa-client-id}&response_type=token&scope=openid&redirect_uri=http://localhost:8080/implicit/callback&state=null&nonce=foo

The token will be in the redirect uri

http://localhost:8080/implicit/callback#access_token={the-token-to-copy}&token_type=Bearer&expires_in=3600&scope=openid&state=null <br/>
Test Our Application:
import our file with File_manager.json and copy uour token to test it with Postman
