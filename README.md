# Web API Slide Notes

## What is an API
- API stands for Application Programming Interface.
- It is a way of allowing two or more applications to communicate and share data.
- Some of the most common API's protocols / conventions are:
    - SOAP (Simple Object Access Protocol).
    - REST (Representational State Transfer).
    - GraphQL.
## REST API
- Operates on the HTTP/s protocol, the protocol that underpins the web.
- Most commonly used alongside JSON to transmit data in the request body.
- Request / Response body can also be HTML, Plain Text, XML or binary data.
- The following HTTP methods are used to perform actions on the server:
    - GET - Get a resource from a server. This could be a single resource, or a collection of resources.
    - POST - Add a resource to a server. This could be a single resource, or a collection of resources.
    - PATCH - Update an existing resource.
    - PUT - Replace an existing resource.
    - DELETE - Remove a resource from the server.
- Example Rest APIs:
    - X (Formerly known as Twitter).
    - Amazon.
    - eBay.
    - Reddit.
## Why Does MK Test have an API?
- It is used to allow for larger setups to communicate between the hub and the satellites.
- Allows for any industry to implement the MK testing equipment seamlessly into their existing software solution.
## What can you do with the MK API?
- Operates on two levels.
    - Test program level.
    - Measurement level.
- Test program level is effectively remotely operating the MK system is a traditional sense.
- Measurement level is directly using the measurement software, and then handling everything in a custom backend written by the customer.
