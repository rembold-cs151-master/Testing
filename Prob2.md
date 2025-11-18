# Problem 2

Connecting to API's is a common action a programmer might want to do, and one you'll be utilizing in Project 5. There are different types of ways in which one can connect to an API, depending on whether you just need to _access_ information from an API (done with a `GET` request), or _send_ information to an API (done with a `POST` request). Here, you will utilize a `POST` request, as that most closely simulates what the NotOpenAI library is doing when you make a request to ChatGPT.

## Step 1: Craft your payload
A `POST` request always needs to send along a bit of formatted information. For this API, you should construct a dictionary payload with the following keys (and then you can fill in your own values):

- `"name"`: what your name is
- `"class_year"`: what year you are (Freshman - Senior)
- `"favorite_animal"`: what your favorite animal is

## Step 2: Connect and Send!

Using the requests library, you want to send a `POST` request to the URL of ???. Doing so means using `requests.post` and then providing both the desired URL and, as a keyword argument of `json`, your payload that you crafted earlier

## Step 3: Interpret the response


## Step 4: Print out **just** the animal fact
