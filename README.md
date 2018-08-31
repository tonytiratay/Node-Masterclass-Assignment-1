# Homework Assignment #1

### The Assignment:

Please create a simple "Hello World" API. Meaning:

1. It should be a RESTful JSON API that listens on a port of your choice. 

2. When someone posts anything to the route /hello, you should return a welcome message, in JSON format. This message can be anything you want. 


### Usage

You can ping ```localhost:3000/hello``` and receive a json message saying "Hello Leslie".

You can also customize the message by sending a name query, and receive a custom message.

EX.

```localhost:3000/hello?name="Tony'"```

You can also pass multiple queries in the url, they will be sent back to you in the json object.

```localhost:3000/hello?name=Tony&title=amazing&other=New stuff```

