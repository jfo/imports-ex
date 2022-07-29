https://caniuse.com/es6-module

Note that a separate network request is fired for each imported module. In the
"old days" this was more of a performance cost, since making a single request
was more expensive. This will be mitigated by HTTP3, which is providing more
true multiplexing for concurrent requests using the same keep-alive connection.

https://blog.cloudflare.com/http3-the-past-present-and-future/

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules
