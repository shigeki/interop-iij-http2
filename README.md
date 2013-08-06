## Information of HTTP/2.0 interop testing for iij-http2

Interop servers for http and https are available as below.


+ http : *NO* Upgrade from HTTP1.1 to HTTP/2.0 , just direct connection start with connection magic and SETTINGS
http://http2.iijplus.jp:8080/

+ https : NPN with protocol name HTTP-draft-04/2.0
https://http2.iijplus.jp:8443/

iij-http2 needs more code cleanup. So it is still in my private repository. Stay tuned for open to public.


