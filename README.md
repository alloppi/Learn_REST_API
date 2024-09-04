# Learn_REST_API

## Characters of REST API
1. Resource-Based
   - Instance / Object, Plurals, i.e. users, products, articles
   - The purpose of URL is easy understandable i.e. https://example.com/users will list all users
2. Uniforrm Interface
   - Operators of http Methods : Get, Post, Put, Patch, Delete
   - Takes standard data exchange format: XML, JSON
3. Stateless
   - The client will provide all the information in the resuest that will sent to server
   - The server will NOT memorised the background context in the request
   - Server will process the service according to each request from client
   - All the request / response are indepencent from another request / reponse cycle
4. Cacheable
   - The result of request are cacheable in
     - Web browser
     - CDN (Cloudflare)
     - In-memory cache (Redis)

## JSON (JavaScript Object Notation)
1. Use for data exchange from System A to System B
2. Key value pair quote by "Double-quote"
   - {"Name":"Alan"}
3. JSON Data Stucture
   - Object: {}, nest objects
   - Array: [], nest arrays
   - string: ""
   - number: 0
   - boolean: true
   - null
