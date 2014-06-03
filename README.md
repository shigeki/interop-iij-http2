## Information of HTTP/2.0 interop testing for iij-http2

Interop servers for HTTP2 draft12 of https and itnermediary are available as below.

+ https : ALPN and NPN with protocol name of h2-12

 https://http2.iijplus.jp/

### Test Pages on http2.iijplus.jp
+ Static Files
+ Print Request Headers
+ HPACK-05 Tests(Ajax needed)
+ Flow Control Tests(Ajax needed)
+ PushPromise Tests
+ Header Tests(Ordering/Cookie) (Ajax needed)
+ Padding Test
+ Frame Compression Test(need SETTINGS_COMPRESS_DATA is 1)

Due to the implementation of stream priority of its dependency and weight, HTTP perfomance is largely degraded.
This is just a prototype to evaluate HTTP/2 functionarities. Need more optimazation.

iij-http2 needs more code cleanup. So it is still in my private repository. Stay tuned for open to public.

If you find any issues, please submit them to this repository.
