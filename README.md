# Context of the project
The brief is made up of two parts, a question part and a second practice part attached to the sentiment analysis brief (https://simplonline.co/briefs/687708b5-17ff-45a3-8934-6de9088fdd76)

In addition to this, you need to know more about it.

++ Questions (embed an answer file in your sentiment analysis project git): ++

### What is HTTP?
* HTTP stands for Hyper Text Transfer Protocol. The communication between client computers and web servers is done by sending **HTTP Requests** and receiving **HTTP Responses**

### What is an API?
* An API is a set of definitions and protocols for building and integrating application software. API stands for **Application Programming Interface**.

APIs let your product or service communicate with other products and services without having to know how they’re implemented. This can simplify app development, saving time and money. When you’re designing new tools and products—or managing existing ones—APIs give you flexibility; simplify design, administration, and use; and provide opportunities for innovation.

### What is the specificity of REST APIs?
* REST is acronym for REpresentational State Transfer. It is architectural style for distributed hypermedia systems and was first presented by Roy Fielding in 2000 in his famous dissertation.
* Guiding Principles of REST

    1. Client–server – By separating the user interface concerns from the data storage concerns, we improve the portability of the user interface across multiple platforms and improve scalability by simplifying the server components.
    2. Stateless – Each request from client to server must contain all of the information necessary to understand the request, and cannot take advantage of any stored context on the server. Session state is therefore kept entirely on the client.
    3. Cacheable – Cache constraints require that the data within a response to a request be implicitly or explicitly labeled as cacheable or non-cacheable. If a response is cacheable, then a client cache is given the right to reuse that response data for later, equivalent requests.
    4. Uniform interface – By applying the software engineering principle of generality to the component interface, the overall system architecture is simplified and the visibility of interactions is improved. In order to obtain a uniform interface, multiple architectural constraints are needed to guide the behavior of components. REST is defined by four interface constraints: identification of resources; manipulation of resources through representations; self-descriptive messages; and, hypermedia as the engine of application state.
    5. Layered system – The layered system style allows an architecture to be composed of hierarchical layers by constraining component behavior such that each component cannot “see” beyond the immediate layer with which they are interacting.
    6. Code on demand (optional) – REST allows client functionality to be extended by downloading and executing code in the form of applets or scripts. This simplifies clients by reducing the number of features required to be pre-implemented.

### What is a URI, an endpoint, an operation?
* A **Uniform Resource Identifier (URI)** is a unique sequence of characters that identifies a logical or physical resource used by web technologies. URIs may be used to identify anything, including real-world objects, such as people and places, concepts, or information resources such as web pages and books. Some URIs provide a means of locating and retrieving information resources on a network (either on the Internet or on another private network, such as a computer filesystem or an Intranet), these are Uniform Resource Locators (URLs). A URL provides the location of the resource
* An endpoint is one end of a communication channel. When an API interacts with another system, the touchpoints of this communication are considered endpoints. For APIs, an endpoint can include a URL of a server or service. Each endpoint is the location from which APIs can access the resources they need to carry out their function.

APIs work using ‘requests’ and ‘responses.’ When an API requests information from a web application or web server, it will receive a response. The place that APIs send requests and where the resource lives, is called an endpoint.

* CRUD vs REST Explained

    The confusion between CRUD and REST stems from the fact that interacting with REST applications often involves the use of CRUD-like functions. This is because REST applications are built around resources (as outlined in the Uniform Interface constraint), which can be created, read, updated, and deleted, just like entries in a collection of data.

    Let’s dive a little deeper. Most of the time, when we talk about REST, we refer to web APIs that adhere to the constraints of REST — or REST APIs. By the nature of REST APIs being served over the web, these APIs communicate with clients using the HTTP protocol, which has its own set of methods for data manipulation: GET, POST, DELETE, PUT, and PATCH, among others. And if you think about it, there’s clearly some overlap between HTTP methods and CRUD functions:

| CRUD  | HTTP |
| ----- | ----- |
| CREATE   | POST   |
| READ   | GET   |
| UPDAE   | PUT/PATCH |
| DELETE   | DELETE   |


### What can be found in the documentation of a rest API?
* The documentation allows you to find the list of endpoints along with the corresponding HTTP verb. 

### Use Postman to make a 3 request on the public API of your choice. Share the requests as well as the answers.

++ Application: ++

* realize a REST API using fast API which for a certain sentence returns the prediction of the sentiment

* publish your application online.
