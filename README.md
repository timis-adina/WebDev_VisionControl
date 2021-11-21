# Exercise 7

_Web Development 2 - University of Luxembourg_  
Adina TIMIS, student number: 0191042056  
Date: 25 November 2021

## What is an REST API?

A REST API is an **application programming interface** (API) that respects the constraints of the REST architecture style in order to interact with RESTful web services. REST means **Representational State Transfer**.

## REST principles

1. Uniform Interface  
   The REST API should ensure that the same piece of data (such as an e-mail address, the name of a user etc) belongs to ony one uniform resource identifier.
2. Client-server decoupling  
   Client and server applications must be completely independant of each other.
3. Statelessness  
   Each request needs to include all the information necessary to process it.
4. Cacheability  
   Resources should be cacheable on the client or server side.
5. Layered system architecture  
   The calls and responses go through different levels and so the REST API need to be designed so that neither the client nor the server can see whether it communicates with the end application or an intermediary.

## How it works

The REST APIs communicate via HTTP requests in order to perform database functions like reading, creating, updating records. The state of a resrouce is known as the resource representation and this information can be delivered to a client in format including JSON, HTML, XLT, Python, PHP or plain text. Request headers and parameters are also important in the REST API since they include important identifier information such as metadata, authorizations, univorm resource identifiers, and much more.
