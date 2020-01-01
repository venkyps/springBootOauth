Authenticate url 
    http://localhost:8080/oauth/authorize?client_id=clientapp&response_type=code&scope=read_profile_info

Access token url
    http://localhost:8080/oauth/token
    
    Headers
    Content-Type  : application/x-www-form-urlencoded
    authorization : Basic Y2xpZW50YXBwOjEyMzQ1Ng==
    
    Body
      formdata
        grant_type  : authorization_code
        code        : RtnhFY(grant code)
        
 Access protected resource
    http://localhost:8080/api/getUserProfile
    
   Headers
      authorization(access token) : Bearer 317a1271-adee-4837-858a-91626bda80e2
   
    
    

