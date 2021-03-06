# Hackathon Resources

## Learning Record Store (LRS)

We will provide access to a LRS for the hackathon. The API for the LRS can be found at

http://46.149.27.91:8080/larissa/xAPI/statements

NB the endpoint for any library is probably the URL minus the statements-part.

API documentation can be found <a href="https://github.com/adlnet/xAPI-Spec/blob/1.0.1/xAPI.md#stmtapi">here</a> as part of the Experience API (xAPI) <a href="https://github.com/adlnet/xAPI-Spec/blob/1.0.1/xAPI.md">1.0.1 specification</a>. Please note that the LRS in place (<a href="https://github.com/Apereo-Learning-Analytics-Initiative/Larissa/">Larissa LRS</a>) only implements the Statements-API (endpoint /statements), as noted in the <a href="https://github.com/Apereo-Learning-Analytics-Initiative/Larissa/blob/master/README.md#xapi-coverage">README</a>.

The LRS comes pre-filled with some generated data to get you started. Credentials for the API are larissa/lrstester.

### Assorted Resources for interacting with the LRS:

* The <a href="http://tincanapi.com/page-developers/"> Tin Can API Developers page</a>. Multiple resource links including links to client libraries.

* <a href="https://github.com/adlnet/xAPI-Dashboard">xAPI-Dashboard</a>. A JavaScript-library for xAPI analysis and chart-generation.

* some <a href="http://www.adlnet.gov/expapi/verbs/">standard verbs</a> for the LRS.

* some <a href="http://blog.saltbox.com/blog/2012/11/28/making-statements-tin-can-api-best-practices/">best practices</a> for creating statements.

* <a href="http://tincanapi.com/wp-content/assets/e-book/Anatomy-of-a-Tin-Can-Statement-e-Book.pdf">Anatomy of a Tin Can Statement</a> is a PDF book containing lots of info and examples on Statement design.
## Open Onderwijs API

An instance of the SURFnet <a href="https://github.com/SURFnet/OpenOnderwijsAPI">Open Onderwijs API</a> will be hosted at

http://46.149.20.182:8000

This API will respond to standard HTTP/1.1 requests with appropriately-formatted data. (An OPTIONS request will return several valid Content-Types for both in- and output, of which it warrants mentioning that the only one appearing in both lists is `"application/json"`.)

As an alternative to rolling your own API requests, SURFnet provides client-libraries for <a href="https://github.com/SURFnet/OpenOnderwijsAPI-js">JavaScript</a>, <a href="https://github.com/SURFnet/OpenOnderwijsAPI-java">Java</a>, and <a href="https://github.com/SURFnet/OpenOnderwijsAPI-ios">iOS</a>.

## Other

* <a href="https://chrome.google.com/webstore/detail/postman-rest-client/fdmmgilgnpjigdojojpjoooidkmcomcm">Postman REST client</a>. A nice tool to verify API interaction.

