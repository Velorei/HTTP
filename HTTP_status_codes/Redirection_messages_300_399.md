|HTTP response status codes (300-399)|Redirection messages|
|---|---|
|300 Multiple Choices|The request has more than one possible response. The user agent or user should choose one of them. (There is no standardized way of choosing one of the responses, but HTML links to the possibilities are recommended so the user can pick.)|
|301 Moved Permanently|The URL of the requested resource has been changed permanently. The new URL is given in the response.|
|302 Found|This response code means that the URI of requested resource has been changed temporarily. Further changes in the URI might be made in the future. Therefore, this same URI should be used by the client in future requests.|
|303 See Other|The server sent this response to direct the client to get the requested resource at another URI with a GET request.|
|304 Not Modified|This is used for caching purposes. It tells the client that the response has not been modified, so the client can continue to use the same cached version of the response.|
|305 Use Proxy Deprecated|Defined in a previous version of the HTTP specification to indicate that a requested response must be accessed by a proxy. It has been deprecated due to security concerns regarding in-band configuration of a proxy.|
|306 unused|This response code is no longer used; it is just reserved. It was used in a previous version of the HTTP/1.1 specification.|
|307 Temporary Redirect|The server sends this response to direct the client to get the requested resource at another URI with the same method that was used in the prior request. This has the same semantics as the 302 Found HTTP response code, with the exception that the user agent must not change the HTTP method used: if a POST was used in the first request, a POST must be used in the second request.|
|308 Permanent Redirect|This means that the resource is now permanently located at another URI, specified by the Location: HTTP Response header. This has the same semantics as the 301 Moved Permanently HTTP response code, with the exception that the user agent must not change the HTTP method used: if a POST was used in the first request, a POST must be used in the second request.|
|||
|||
|See also|[HTTP response status codes](https://github.com/Velorei/HTTP/blob/main/HTTP_status_codes/HTTP_status_codes.md)|
