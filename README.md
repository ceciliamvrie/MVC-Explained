First, I would like to say thank you Matius for introducing to me this quote:
`"Writing is nature's way of exposing how sloppy your thinking is." ~Guindon`
With that said, I will be teaching you with the best of my abilities exactly what I think MVC is...

# What is MVC?
To start off with, MVC stands for the words Model View Controller, which we will get back to later.
MVC is essentially an architectural paradigm, meaning that it is a way to think about, and structure 
your web applications. 
Developers typically use paradigms as means for structuring and ordering their development projects.
This does not mean that paradigms are frameworks! Frameworks infact use paradigms for their own structure,
and so it's best if one learns first that framework's paradigm before they get to know their framework.

### Why MVC?
MVC is one of the most popular architectures out there, if not the most popular architecture out there 
for developing web applications. The reason is because of how it is based off of the 'flow' of a website, 
meaning the transfer or flow of data from the client, to the server, to the database, back to the server,
and to the client again. 
If this didn't just give you the ultimate 'aha!' moment, then that means that we probably need to spend a 
little more time on what the client, the server, and the database all mean. 

- Client: The client is basically the user interacting with the browser. The client never sees the database and can only send requests to the server. The languages that make up the client side are the markdown languages, aka HTML & CSS, and Javascript.
- Server: The server is the 'middleman' that's sandwiched between both the client and the database. It sends requests from the client to the database and then sends back data from the database to the client on how to display that data. The server can not take the place of the database because it cannot hold any information itself for a 'longterm' period.
- Database: The database is incharge of storing longterm data of which the client can pull up. It never gets to interact with the client itself, as it can only interact with the server. 
                                                                  
### How does MVC connect?
MVC can be thought of in the same way as the client, server, and database since you have one part 
controlling the 'view', one part controlling the middleman, and another acting as the database. Here, why don't
we get into a little more depth...

- Model: Controls all interactions with the data, such as storing, or recieving data from the database. Like the database, the model only interacts with the controller.
- View: The view is composed of everything that gets rendered onto the browser, meaning that is is basically everything that the user sees, and the only thing that the user can see. This is incharge of displaying information to the user, and it can only interact with the controller. 
- Controller: The controller is arguably the most important part of MVC as it is in charge of taking info from the user, processing it, sending it to the model, and sending it back to the view as information on how it should compile the data. 
