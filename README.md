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
    - 
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
