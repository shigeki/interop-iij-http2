## Information of HTTP/2.0 interop testing for iij-http2

Interop servers for HTTP-draft-06/2.0 in http and https are available as below.


+ http : Direct Connection or Upgrade from HTTP1.1 to HTTP/2.0

  http://http2.iijplus.jp:8080/

+ https : ALPN and NPN with protocol name HTTP-draft-06/2.0

 https://http2.iijplus.jp:8443/

### Pages
+ Static Files
+ Print Request Headers
+ HPACK-03 Tests(Ajax needed)
+ Flow Control Tests(Ajax needed)
+ PushPromise Tests

iij-http2 needs more code cleanup. So it is still in my private repository. Stay tuned for open to public.

If you find any issues, please submit them to this repository.
