# Learn_REST_API

## Characters of REST API
1. Resource-Based
   1.1 Instance / Object, Plurals, i.e. users, products, articles
   1.2 The purpose of URL is easy understandable i.e. https://example.com/users will list all users
2. Uniforrm Interface
   2.1 Operators of http Methods : Get, Post, Put, Patch, Delete
   2.2 Takes standard data exchange format: XML, JSON
3. Stateless
   3.1 The client will provide all the information in the resuest that will sent to server
   3.2 The server will NOT memorised the background context in the request
   3.3 Server will process the service according to each request from client
   3.4 All the request / response are indepencent from another request / reponse cycle
4. Cacheable
   4.1 The result of request are cacheable in
     4.1.1 Web browser
     4.1.2 CDN (Cloudflare)
     4.1.3 In-memory cache (Redis)
