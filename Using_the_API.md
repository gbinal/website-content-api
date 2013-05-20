### Using the API

The example below is written with C#, using .NET 4.0.  

The API supports REST formatted requests, and can provide a response in JSON format, depending upon the content type specified in the request header.  

* JSON Response = Content-Type:application/json
* XML Response = Content-Type:text/json

The examples are for JSON-formatted responses.  

Making the request to the REST service involves a simple HTTP request and response. The following is a simple method that makes an [HTTP](http://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) request using the [URL](http://en.wikipedia.org/wiki/Url) provided and returns an HttpWebResponse object. The HttpWebRequest and HttpWebResponse objects are part of the System.Net namespace.  

_**}**_  

_**Page.Controls.Add(_placeHolder);**_  
