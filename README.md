Postman APIs

http://localhost:8080/api/auth/signup

Post->Raw
```
{
"username":"purabdk01",
"email":"admin@admin.com",
"password":"password"
}
```

Used following dummy smtp server for testing
https://mailtrap.io/

http://localhost:8080/api/auth/login
```
{
	"username":"purabdk04",
	"password":"password"
}
```
Response sample:
```
{
    "authenticationToken": "eyJhbGciOiJSUzI1NiJ9.eyJzdWIiOiJwdXJhYmRrMDQiLCJpYXQiOjE2MzY4OTQ4MjMsImV4cCI6MTYzNjg5NDkxM30.IYk-FkzxCyRGOkZDNLYrajEqDojXTj5JVK7P6B5E4Jl3bYoR-d5oprPOL46vvx6C3urtGISkh1jIysTiud7XJLAINULFfzVpDwbwPAiCCZD6C737xJUo2s5z5DmOEhQ4sNbOIg0QxHlCaREX7JXbWO64kUVceCv98UXnPcVv6_hRwEc-NP3b0gHmRaBWByLcKNbwNoq1gclw9xCIlFjM8s2Hs22ubtiNFde52YPkXXB0pXSdMeKw9RaJ7lGeUIyDf2u14C0B-i1vqJUYJ4Cs4yeMDKXkHZh8bcvqjdTwiVuKEzKk7s742_M7vmXCWHeYmgJ0L5GgnHYFdefTFzIq-g",
    "username": "purabdk04"
}
```
POST- http://localhost:8080/api/subreddit
```
{  
    "name": "first superredidd",
    "description": "first description"  
}
```