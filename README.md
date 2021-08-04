# REST.API-HTTP-intro
What is REST#
Representative State Transfer
Convention over HTTP
Key characteristics#

-----------------------------------------------------------------------------------------------
Resource based (server pages, records in database)

Use URLs as unique identifiers

Stateless ("session" state transferred in request/response and not hold on server side)

Common representations: HTML, XML, JSON

HTTP usage#
-----------------------------------------------------------------------------------------------
resource identifier – HTTP path (/posts, /tasks/42, /posts/123/comments)

action – HTTP method (GET, POST, PUT, PATCH, DELETE, HEAD)

resource representation (JSON, HTML) – request and/or response body

meta information – headers (authentication, caching, content type)

action result status – HTTP status codes

HTTP method mapping to actions against resource#
-----------------------------------------------------------------------------------------------
GET – get

POST - create

PUT – replace

PATCH – partial update

DELETE – delete

Common status codes#
-----------------------------------------------------------------------------------------------
200 OK

201 Created

400 Bad request (malformed body)

401 Not authenticated

403 Not authorized

404 Resource not found

422 Unprocessable entity (server side validation failed)

500 Internal server error
