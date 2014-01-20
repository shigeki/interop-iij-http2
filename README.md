## Information of HTTP/2.0 interop testing for iij-http2

Interop servers for HTTP-draft-09/2.0 in http and https are available as below.

+ https : ALPN and NPN with protocol name of HTTP-draft-09/2.0

 https://http2.iijplus.jp/

+ intermediary: proxy of https(HTTP-draft-09/2.0)->http(HTTP/1.1) to http://www.iij.ad.jp/

 https://http2-proxy.iijplus.jp/

### Test Pages on http2.iijplus.jp
+ Static Files
+ Print Request Headers
+ HPACK-05 Tests(Ajax needed)
+ Flow Control Tests(Ajax needed)
+ PushPromise Tests
+ Header Tests(Ordering/Cookie) (Ajax needed)

iij-http2 needs more code cleanup. So it is still in my private repository. Stay tuned for open to public.

If you find any issues, please submit them to this repository.
