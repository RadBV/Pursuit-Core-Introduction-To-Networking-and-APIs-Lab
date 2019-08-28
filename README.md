# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


- 200

1. 
2. This code means the HTTP request was received, approved and successfully delivered to the user.
3. This code doesn't present any problem and doesn't need fixing.

- 301

1.
2. This code means the location for the request made has been moved permanently to another URL.
3. If I encountered this problem in my app, I would update whatever URL I used for the request to the correct URL.

- 400

1.
2. This code means that the request put in can't be processed due to an error on the user's part (wrong syntax).
3. If I get this error, I should probably check the way I wrote everything down and make sure everything is correct. If It still didn't work then the info that I was using was not correct, I'd need to find out more information.

- 401

1.
2. This code is to let the user know that they are unauthorized in accessing the target resource that requested. Specifically used for when the user needs to give authentication.
3. I would look for ways to autheticate my use of whatever the requested resource was.

- 403

1.
2. This code is similar to 401. It means that the user is forbidden from accessing the target resource, most likely because they don't have the required permission or the server/host denied authentication given.
3. I can't really do anything to fix this error other than ask the server/host to pretty please let me have their resource.

- 404

1.
2. This code means the request was received by the server, but the specific resource requested could not be found on that server.
3. I would move up one directory at a time until I am returned with something, then figure out where exactly in that directory is the resource I'm looking for.

- 418

1.
2. This code is part of the HTCPCP (Hyper Text Coffee Pot Control Protocol) and occurs when a user tries to use brew coffee in a teapot.
3. Solution: Stop brewing coffee in teapots.

- 500

1.
2. This code means there was some kind of error with the server a user requested resources from.
3. An internal server error can only really be fixed by the server owner. If I owned the server, I'd look into the error. Otherwise all I can do is contact the owner of the website/server and let them know there was a problem.


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?


For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. https://lmgtfy.com/?q=cat+fact+api

1. A random cat fact
1. A list of 150 random users in English.
1. The current stock price of Microsoft. (IEX API)
1. The 5 year history of Apple stock prices (IEX API)
1. All the Swift language repos on Github with Pursuit in their name
1. A list of all Pokemon
1. A list of all items in Fortnite
1. A list of all Game of Thrones Episodes.
1. A list of all songs with "Love" in the title.
1. All information about Petyr Baelish from the Game of Thrones books
1. All the movies Leonardo Dicaprio has acted in
