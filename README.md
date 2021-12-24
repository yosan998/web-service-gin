# web-service-gin
The basics of writing a RESTful web service API with Go and the Gin Web Framework (Gin) from https://go.dev/doc/tutorial/web-service-gin

The tutorial includes the following sections:
1. Design API endpoints.
2. Create a folder for your code.
3. Create the data.
4. Write a handler to return all items.
5. Write a handler to add a new item.
6. Write a handler to return a specific item.

Here are the endpoints I have created:
1. /albums
 - GET – Get a list of all albums, returned as JSON.
 - POST – Add a new album from request data sent as JSON.
2. /albums/:id
 - GET – Get an album by its ID, returning the album data as JSON.
