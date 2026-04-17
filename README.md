# hng14-stage-2

1. What the project is and how to run it locally
This project is about building API and using Nginx to properly route the different APIs. The API could be built using any programming of our choice. I used NodeJs to build.
To run it locally, I used the curl command to test the different APIs

2. The three endpoints and their expected responses
The first endpoint was GET /
TO test it i used the "curl -I http://localhost:3000/" and the output was 
HTTP/1.1 200 OK
X-Powered-By: Express
Content-Type: application/json; charset=utf-8
Content-Length: 28
ETag: W/"1c-0Y4Ez9mUrgegww+RKJZgbzzx7wk"
Date: Fri, 17 Apr 2026 12:05:06 GMT
Connection: keep-alive
Keep-Alive: timeout=5

To test the second Endpoint GET /health 
i used "curl -I http://localhost:3000/health"
and the output was 
hngdevops@ip-10-0-7-209:~/NodeApp/app$ curl -I http://localhost:3000/health
HTTP/1.1 200 OK
X-Powered-By: Express
Content-Type: application/json; charset=utf-8
Content-Length: 21
ETag: W/"15-ddTYsdHY+0pb5BUv18Z3zrCXnEY"
Date: Fri, 17 Apr 2026 12:06:10 GMT
Connection: keep-alive
Keep-Alive: timeout=5


To test the third Endpoint GET /me 
i used "curl -I http://localhost:3000/me"
And the output was
hngdevops@ip-10-0-7-209:~/NodeApp/app$ curl -I http://localhost:3000/me
HTTP/1.1 200 OK
X-Powered-By: Express
Content-Type: application/json; charset=utf-8
Content-Length: 115
ETag: W/"73-/dBTdzGNbzitA6kd+6s/EPiow+M"
Date: Fri, 17 Apr 2026 12:07:02 GMT
Connection: keep-alive
Keep-Alive: timeout=5


3.My live deployment URL:
https://kene3101.duckdns.org/
