# Simple app
This is a simple web app that returns counter on how many times page has been seen.
The application is using redis to store the count.

It also has anendpoint protected by basic http auth that will provide you with a secret string.

## How to start locally
docker-compose up

## Endpoints
* GET / - path shows hello message with a counter on how many time the page has been visited.
* GET /tellmeasecret - this path requires basic http authentication and it will tell you a super secret.


URL:
```
http://a7282a3fa6c2011ea87240675bdf3dc0-172239269.eu-west-1.elb.amazonaws.com
```
