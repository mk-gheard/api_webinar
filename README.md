## What is an API
- API stands for Application Programming Interface.
- Set of rules and protocols that allows one software application to interact with another.
- APIs serve as an interface that enables different software systems to communicate with each other. They define the way requests are made and how responses should be formatted.
- Defines the methods and data structures that developers can use to communicate with the operating system, libraries, or other services.
- APIs provide an abstraction layer, which hides the underlying complexity of operations, allowing developers to perform actions without needing to understand how the internal processes work.
- Types of API:
    - Web APIs: These are accessed over a network using HTTP/HTTPS and are commonly used for web services. Examples include RESTful APIs and SOAP APIs.
    - Library APIs: These are provided by software libraries to allow applications to use their functions.
    - Operating System APIs: These allow applications to interact with the operating system.
## REST API
- A REST API, or Representational State Transfer API, is a type of web API that adheres to the principles of REST, an architectural style for designing networked applications.
- Key REST Characteristics:
    - Stateless: Each API call from the client to the server must contain all the information needed to understand and process the request. The server does not store any client context between requests.
    - Client-Server Architecture: The client and server operate independently, with the client responsible for the user interface and the server managing data storage and processing. This separation allows for 
      more scalability and flexibility in development.
    - Uniform Interface: REST APIs use a consistent and standard interface for communication, typically relying on HTTP methods (such as GET, POST, PUT, DELETE) and standard URL structures.
    - Resource-Based: REST APIs focus on resources, which are any kind of object, data, or service that can be accessed by the client. Each resource is identified by a unique URL.
    - Representation of Resources: Resources can have multiple representations, such as JSON, XML, or HTML. The client can specify which representation it prefers using HTTP headers.
- Key Components of REST:
    - Endpoint: The URL where the API can be accessed. Each endpoint corresponds to a specific resource or collection of resources.
    - HTTP Methods: Standard methods used in RESTful interactions:
        - GET: Retrieve information about a resource.
        - POST: Create a new resource.
        - PUT: Update an existing resource.
        - DELETE: Remove a resource.
    - Request/Response Headers: Used to pass additional information with the request or response, such as content type and authentication credentials.
    - Request/Response Body: The data sent to or received from the server, often in JSON or XML format.
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
