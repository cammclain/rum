# Rum Framework

---
To make a full stack web framework

## Motivation: 
I want to create a project that could be best compared to [Reflex](https://reflex.dev/) (formerly pynecone).

`Reflex` is extremely similar to `React`, however you create `Reflex` sites using only `Python`.

I want to write this in `Go`, as one of the primary goals of this `full stack web framework` is to make a framework that is faster than `Reflex`. `Reflex` is insanely slow to render.

## Goal:
I want to create a component driven system that breaks down the UI into just that. components. 

Ideally you would be able to write an entire application in pure Go, and it would use the `Rum` framework to render it.


however the goal is to create the framework without using **any** `client side scripting`.



Often times these frameworks rely on *excessive* if not **exclusive** use of `JavaScript` or other client side scripting languages 
I hate that.

We want to avoid running any code on the client side and instead rely on the tools provided by `Go` (we will often reference Githubs awesome-go list), and the `Gin web framework` to create the functionality we are looking for.


For example, the Gin-Contrib organization has many different packages that can be used to implement things like:
- Auth
- Multi-Templating
- CORS
- WebSockets
- Server-Sent Events
- etc


 
## Components System:

We want to use `HTML` & `CSS` to create components using advanced templating methods and techniques such as Gin multi-template

We want to use 
- Server Sent Events
- websockets
- simply reloading the page 
- advanced `CSS` styling techniques 
To replace the dynamic functionality of `JavaScript`, whether that be reactive elements on the HTMl, or sending data to and from the server.


We want to implement the logic using Go.




