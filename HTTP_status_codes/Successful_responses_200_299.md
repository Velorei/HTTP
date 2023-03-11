|HTTP response status codes (200-299)|Successful responses|
|---|---|
|200 OK|The request succeeded. The result meaning of "success" depends on the HTTP method:<br/>GET: The resource has been fetched and transmitted in the message body.<br/>HEAD: The representation headers are included in the response without any message body.<br/>PUT or POST: The resource describing the result of the action is transmitted in the message body.<br/>TRACE: The message body contains the request message as received by the server.|
|201 Created|The request succeeded, and a new resource was created as a result. This is typically the response sent after POST requests, or some PUT requests.|
|202 Accepted|The request has been received but not yet acted upon. It is noncommittal, since there is no way in HTTP to later send an asynchronous response indicating the outcome of the request. It is intended for cases where another process or server handles the request, or for batch processing.|
|203 Non-Authoritative Information|This response code means the returned metadata is not exactly the same as is available from the origin server, but is collected from a local or a third-party copy. This is mostly used for mirrors or backups of another resource. Except for that specific case, the 200 OK response is preferred to this status.|
|204 No Content|There is no content to send for this request, but the headers may be useful. The user agent may update its cached headers for this resource with the new ones.|
|205 Reset Content|Tells the user agent to reset the document which sent this request.|
|206 Partial Content|This response code is used when the Range header is sent from the client to request only part of a resource.|
|207 Multi-Status (WebDAV)|Conveys information about multiple resources, for situations where multiple status codes might be appropriate.|
|208 Already Reported (WebDAV)|Used inside a <dav:propstat> response element to avoid repeatedly enumerating the internal members of multiple bindings to the same collection.|
|226 IM Used (HTTP Delta encoding)|The server has fulfilled a GET request for the resource, and the response is a representation of the result of one or more instance-manipulations applied to the current instance.|
|||
|||
|See also|[HTTP response status codes](https://github.com/Velorei/HTTP/blob/main/HTTP_status_codes/HTTP_status_codes.md)|
