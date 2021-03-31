# Sending Form Data

basically a web browser sends a request to the server and that server answers the request using a protocol.

The two most important attributes are action and method

## Attribute

defines where the data gets sent. Its value must be a valid relative or absolute URL
If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.

_Absolute URL_

`<form action="https://example.com">`

_Relative URL_

`<form action="/somewhere_else">`

_NO Attributes_

`<form>`

## Get And Post Methods

### GET:

method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource."

### POST:

the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result."
When the form is submitted using the POST method, you get no data appended to the URL, and the HTTP request looks like so, with the data included in the request body instead:

> POST / HTTP/2.0
>
> Host: foo.com
>
> Content-Type: application/x-www-form-urlencoded
>
> Content-Length: 13
>
> say=Hi&to=Mom
