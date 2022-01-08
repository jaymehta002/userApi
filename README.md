# userApi
<br>
signup: localhost:4000/user/signup<br>
<br>
{<br>
    "username": "username",<br>
    "email" : "abc@xyz.com",<br>
    "password" : "12345678"<br>
}<br>
<br>
login: localhost:4000/user/login<br>
<br>
{<br>
    "email": "abc@xyz.com",<br>
    "password": "12345678"<br>
}<br>
<br>
get details: localhost:4000/user/me<br>
<br>
Headers<br>
<br>
Content-Type: application/json<br>
token: "YOUR-TOKEN-VALUE"<br>
