# Fetching details about the user data

 ### sample data:
[{
"id":1,
"name": "SHANKAR",
"age": 10,
"dob": "20-10-2020",
"firstName": "shankar",
"lastName": "s",
"more": {
"address_line1": "16E",
"address_line2": "west ramanathapuram",
"address_line3": "dindigul,624001",

"phone": "9876578765"
}
},
{
"id":2,
"name": "vidyut",
"age": 17,
"dob": "20-10-2002",
"firstName": "vidyut",
"lastName": "d",
"more": {
"address_line1": "88T",
"address_line2": "RM colony",
"address_line3": "dindigul,624001",
"phone": "93456276546"
}
}]

## URL created:

https://myuser.free.beeceptor.com

>curl -v -X GET 'https://myuser.free.beeceptor.com/my/api/path' -H 'Content-Type: application/json' '
>curl -v -X GET 'https://myuser.free.beeceptor.com/id=1' -H 'Content-Type: application/json' '
>curl -v -X GET 'https://myuser.free.beeceptor.com/id=2' -H 'Content-Type: application/json' '

