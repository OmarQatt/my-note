# Readings: Express

# Review, Research, and Discussion

## What's the difference between PUT and PATCH?
PUT: method of modifying resource where the client sends data that updates the entire resource.
PATCH: you are only required to send the data that you want to update, and it won’t affect or change anything else.

## Provide links to 3 services or tools that allow you to "mock" an API for development like json-server
1- [Stoplight](https://pages.github.com/).
2- [Mocky](https://pages.github.com/).
3- [Beeceptor](https://pages.github.com/).

## Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
apiDocjs: Inline Documentation for RESTful web APIs. It creates a documentation from API annotations in your source code. It includes a default template which uses handlebars, Bootstrap, RequireJS and jQuery for the output of the generated apidata.js and apiproject.js as a html-page;
```
 description: OK
        '400':
          description: Bad request. User ID must be an integer and larger than 0.
        '403':
          description: forbidden.
        '404':
          description:  not found.
        '500':
          description: Server error.
 ```   
 
Swagger Inspector: Test and Document Your APIs With Ease. It is a free cloud-based API testing and documentation tool to simplify the validation of any API and generate its corresponding OpenAPI documentation.
```
 description: OK
        '400':
          description: Bad request. User ID must be an integer and larger than 0.
        '401':
          description: Authorization information is missing or invalid.
        '404':
          description: A user with the specified ID was not found.
        '500':
          description: Unexpected error.
 ```   
## Compare and contrast SOAP and ReST

| SOAP  | ReST |
| ------------- | ------------- |
| SOAP stands for Simple Object Access Protocol  | REST stands for Representational State Transfer  |
| SOAP is a protocol. SOAP was designed with a specification. It includes a WSDL file which has the required information on what the web service does in addition to the location of the web service.  | REST is an Architectural style in which a web service can only be treated as a RESTful service if it follows the constraints of being
Client Server
Stateless
Cacheable
Layered System
Uniform Interface  |
| SOAP cannot make use of REST since SOAP is a protocol and REST is an architectural pattern.  | REST can make use of SOAP as the underlying protocol for web services, because in the end it is just an architectural pattern.  |
| SOAP can only work with XML format. As seen from SOAP messages, all data passed is in XML format.  | REST permits different data format such as Plain text, HTML, XML, JSON, etc. But the most preferred format for transferring data is JSON.  |

Refernce: https://www.guru99.com/comparison-between-web-services.html

# Preview

## Which 3 things had you heard about previously and now have better clarity on?
DB
useState
API

## Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
 API (Fetch API)
 Middleware
 more about CSS && Sass
 
 ## What are you most excited about trying to implement or see how it works?
 Middleware & Api, build fully website having admin and user. 
