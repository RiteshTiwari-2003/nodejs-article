#### what is the node js , basiv introduction of nodejs?
1. node js is basically open-source , server side javascript runtime.
2.  Allow you to run javascript on your machine or servers.
3.  Built on the V8 javascript engine for speed 
4. robust ecosystem with npm 

### what is the open source?
open source means that the source code of nodejs is publically available .

anyone can :
view : you can see how nodejs is built under the hood 
modify: if you want to customize or improve node js , you can do it .
contribute :
developer around the world actively contribute to improving node js.

### what is cross platform ?
cross platform means node.js can run on multiple operating system without needing major changes 

### what is javascript run time envoirment?
javascript runtime envoirment refers to the envoirment where your javascript code runs 
in browser : javascript typically runs on the browser (like chrome or firefox) to handle frontend tasks.
with nodejs : 
node js allow javascript to run outside the browser , on the server .
it provides tools to interact with system , like:
file system (read/write file)
network (handle http requests0)
databse (connect to databse like mongo or mysql)

## why nodejs special as a runtime ?
v8 engine:
nodejs use google chrome's v8 engine to compile javascript into machine code, making it lighting fast .
Built in apis:
node js comes with builtin apis (like fs for file system or http for server) so you can build powerfull application without extra libraries .

### why do we need nodejs?
single language for full stack development :
developers can use javascript for both frontend and backend , reducing complexity .
for exampe , a mern stack project (mongodb , express , react, node)

high performance :
thanks to v8 engine , nodejs is super fast .
it can handle thousand of simultaneous connection with ease

event driven and non blocking i/o:
unlike traditional servers that block a thread for each requrest , nodejs uses asynchronous model , making it highly efficient for handling multiple tasks 

### is it a language or framework?
Nodejs  is neither a language nor framework , but rather a javascript runtime envoirment that allows developers to run javascript outside of browser .

## some famous npm packages 
express.js: a popular framework for building web application and APIs,
mongoose: a package for interacting with mongodb database using an object data modeling (odm) approach.
axios: a promise based http client for making api request
react (and React DOM): through originally developed for the browser, react can be installed via npm for building modern web application 

socket.io: enables real time communication between client and servers .
passport.js: authentication middleware for ndejs

# global and window in nodejs
Did you know that javascript behave differently in the browser and in nodejs 
like inspect cick karke jab mai browser me window write karta hu aur hit karta hu to i got a Window object in which many property og object Window object present 


### module in node js 
self contained code unit:
each file in node is treated as a seperate module. 
variable , functioon or object defined in one file are not accessible in another file by default unless you explicitly export them 

Encapsulation :
Node js uses the commonJS module sysytem (module.exports and require)
to ensure the code in one file does not pollute or interfere with the global scope 

this make your code modular  maintainable and easier to debug 

### what exactly is a module in node.js ?
a module in nodejs represents a file containing code that is self contained , reusable and encapsulated 
node js uses the commonJS module system 
this module system came before ES Modules was introduced in javascript, thats why its syntax is diffeerent 
modules in node js are created by defining seperate files for different functionality  

you must export anything you want to make accessable to other modules 

