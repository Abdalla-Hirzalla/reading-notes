# Readings: REST

## Who is Roy Fielding?

He helped write the first web servers, that sent documents across the internet… and then he did a ton of research explaining why the web works the way it does. His name is on the specification for the protocol that is used to get pages from servers to your browser.


## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

The protocol I mentioned, that he helped write, HTTP, it's capable of all sorts of neat stuff that people ignore for some reason.

## What is the HTTP protocol that Fielding and his friends created?


 That first part tells the browser what protocol to use. That stuff you type in there is one of the most important breakthroughs in the history of computing.Because it is capable of describing the location of something anywhere in the world from anywhere in the world. It's the foundation of the web. You can think of it like GPS coordinates for knowledge and information.For anything really. That guy, Roy Fielding, he talks a lot about what those things point to in that research I was talking about. The whole world wide web is built on an architectural style called “REST”.

## What does a GET do?


REST provides a definition of a “resource”, which is what those things point to.A web page is a “representation” of a resource. Resources are just concepts. URLs--those things that you type into the browser...

## What does a POST do?


If one system needs to add something to another system, it would use an HTTP verb of **POST**.

## What does PUT do?

If a system wants to replace something in another system, it uses an HTTP verb of **PUT**.


## What does PATCH do?

 to do a partial update, it'll hopefully use **PATCH**. The only thing left to figure out is what the data models should look like.
