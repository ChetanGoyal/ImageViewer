Providing UserId and access token in Config.js

I tried to generate the code by following the steps provided in the developer platform by facebook. I tried to generate the code but with https://www.upgrad.com, the code
was not getting generated due to which i was not able to work on creating the access token by running the CURL requests via Postman.
  
  I tried to run 
  the https://api.instagram.com/oauth/authorize
  ?client_id={app-id}
  &redirect_uri=https://www.upgrad.com
  &scope=user_profile,user_media
  &response_type=code
  
  and I got the below page : https://www.upgrad.com/ca/#_
  This didn't has the code which has to be used in further steps.
