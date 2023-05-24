# Class-12 Reading Notes

## PLACEHOLDER1

> 1. ***In your own words, describe what each group of status code represents:***
>   100’s = The 100-series status codes are informational responses.
    200’s = The 200-series status codes are success responses.
    300’s = The 300-series status codes are redirection responses.
    400’s = The 400-series status codes are client error responses.
    500’s = The 500-series status codes are server error responses.
>
> 2. ***What is a status code 202?***
> It indicates that the server has received the request from the client and has understood it, but the processing of the request is not yet complete. meaning its probably somewhere stuck in promises.
>
> 3. ***What is a status code 308?***
> The new URL or URI where the requested resource can be found.
>
> 4. ***What code would you use if an update didn’t return data to a client?***
> 204
>
> 5. ***What code would you use if a resource used to exist but no longer does?***
> 410
>
> 6. ***What is the ‘Forbidden’ status code?***
> You guys make it sound like a spell but its 403 it just means that the client doesn't have access or that that the server is refusing to for fill the request.
>

## PLACEHOLDER2

> 1. ***Why do we need to pull our MongoDB database string out of our server and put it into our .env?***
> so that it doesn't get compromised and when we use it we don't want it to be a localhost
>
> 2. ***What is middleware?***
> code that runs when the server gets a request but before it gives a response.
>
> 3. ***What does app.use(express.json()) do?***
> it lets our server accept json 
>
> 4. ***What does the /:id mean in a route?***
> Used as a placeholder to represent a dynamic parameter or variable value in the URL. The :id is a common naming convention, but it can be replaced with any meaningful identifier depending on the specific application or use case.
>
> 5. ***What is the difference between PUT and PATCH?***
> Both kinda work the same but one put  replaces while patch partially updates
>
> 6. ***How do you make a default value in a schema?***
>To set a default value in a schema, you need to define it during the schema definition or configuration
>
> 7. ***What does a 500 error status code mean?***
> it a general catch all error code that could mean anything from results not found to a third party service failure
>
> 8. ***What is the difference between a status 200 and a status 201?***
> 201 is typically returned in response to a POST request to indicate that a request was successful, resulting in the creation of a new resource on the server.

while 200 is a all good request that is used for a GET request.
>

## Things I want to know about
