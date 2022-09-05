
![](https://s.brightspace.com/lib/bsi/20.22.8-212/images/tier1/arrow-collapse.svg)Hide Assignment Information

Instructions

# Readings: Express

Below you will find some reading material, code samples, and some additional resources that support today's topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

## [](https://github.com/LTUC/asac-advanced-js-c01/blob/main/classes/class-02/DISCUSSION.md#review-research-and-discussion)Review, Research, and Discussion

In your reading notes page for this class, provide answers to the following prompts. Cite any external sources

1.  What's the difference between `PUT` and `PATCH`?
- Put : Is  **used to send data to a server to create/update a resource**. The difference between POST and PUT is that PUT requests are idempotent. That is, calling the same PUT request multiple times will always produce the same result.
- PATCH: PATCH is  **a method of modifying resources where the client sends partial data that is to be updated without modifying the entire data**.
2.  Provide links to 3 services or tools that allow you to "mock" an API for development like `json-server`
- Nock
- MockServer
- Beeceptor
3.  Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?
*swagger* is 400 for successful and 401, for unsuccessful
*APIDoc.js*   [Successful responses](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#successful_responses)  (`200`–`299`) and   [Server error responses](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#server_error_responses)  (`500`–`599`)
4.  Compare and contrast SOAP and REST <br>
*There are 2 alternative methods for transmitting data online: REST and SOAP. Both specifically outline the creation of application programming interfaces (APIs), which permit data exchange across web applications. Several architectural tenets make up the Representational State Transfer (REST) framework. The World Wide Web Consortium (W3C) maintains the official standard known as simple object access protocol (SOAP) (W3C). The primary distinction is that REST is not a protocol, but SOAP is. Depending on the use case and developer preferences, an API will usually conform to either REST or SOAP.*

| SOAP| REST|
| ------ | ------ |
|A client-server architecture composed of clients, servers, and resources.|**Web services security (WS-security)**: Standardizes how messages are secured and transferred through unique identifiers called tokens. |
|[Stateless](https://www.redhat.com/en/topics/cloud-native-apps/stateful-vs-stateless)  client-server communication, meaning no client content is stored on the server between requests. Information about the session’s state is instead held with the client.|**WS-ReliableMessaging**: Standardizes error handling between messages transferred across unreliable IT infrastructure.|
|Cacheable data to eliminate the need for some client-server interactions.|**Web services addressing (WS-addressing)**: Packages routing information as metadata within SOAP headers, instead of maintaining such information deeper within the network.|
|A layered system constraint, where client-server interactions can be mediated by hierarchical layers.|**Web services description language (WSDL)**: Describes what a web service does, and where that service begins and ends.|

### [](https://github.com/LTUC/asac-advanced-js-c01/blob/main/classes/class-02/DISCUSSION.md#document-the-following-vocabulary-terms)Document the following Vocabulary Terms

Term

Web Server

Express

Routing

WRRC

## [](https://github.com/LTUC/asac-advanced-js-c01/blob/main/classes/class-02/DISCUSSION.md#preview)Preview

Skim the following materials in preparation for the upcoming lecture. Note the following as you browse the material, and be prepared to participate in discussions during lecture

1.  Which 3 things had you heard about previously and now have better clarity on?
- React testing only.
2.  Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- Everything.
3.  What are you most excited about trying to implement or see how it works?
*Each front and back end with no failures in running them*

### [](https://github.com/LTUC/asac-advanced-js-c01/blob/main/classes/class-02/DISCUSSION.md#preparation-materials)Preparation Materials

-   [An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction){:target="_blank"}
-   [What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm){:target="_blank"}
-   [What is TDD?](https://www.agilealliance.org/glossary/tdd/){:target="_blank"}
-   [CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8){:target="_blank"}

#### [](https://github.com/LTUC/asac-advanced-js-c01/blob/main/classes/class-02/DISCUSSION.md#bookmark)Bookmark

-   [nodeJS docs](https://nodejs.org/en/docs/){:target="_blank"}
-   [npm docs](https://docs.npmjs.com/){:target="_blank"}
-   [express docs](https://expressjs.com/en/4x/api.html){:target="_blank"}
-   [http status codes](https://www.restapitutorial.com/httpstatuscodes.html){:target="_blank"}
-   [supertest](https://github.com/visionmedia/supertest){:target="_blank"}
