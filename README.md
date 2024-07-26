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
    - AWS.
    - Azure.
## Why Does MK Test have an API?
- It is used to allow for larger setups to communicate between the hub and the MK Test Systems.
- Allows for any industry to implement the MK testing equipment seamlessly into their existing software solution. (As long as the test doesn't require operator input.)
## What can you do with the MK API?
- Operates on two levels.
    - Test program level.
    - Measurement level.
- Test program level is effectively remotely operating the MK system is a traditional sense.
- Measurement level is directly using the measurement software, and then handling everything in a custom backend written by the customer.
## Case Study: Airbus
- Airbus have large networks of connected test systems that all report back to a central controlling unit with the API exposed.
- Similiar to Siemens, they then have an application layer that pulls all data and handles that in their systems.
## Case Study: Siemens Magnets for MRI Machines
- In process of implementation. Not yet complete.
- They have a SAP based system that they needed to integrate with MK.
- Custom software was written called Middleman that was responsible for managing the communication between SAP and MK API.
- Allowed for the MK system integrated seamlessly into their workflow.
