# kurijn.github.io

$ curl -I https://kurijn.github.io  
HTTP/2 200 &rarr; HTTP/2 (or higher) is very desirable.  
server: GitHub.com  
content-type: text/html; charset=utf-8  &rarr; we have an html file (containing RDFa triples as Turtle)  
permissions-policy: interest-cohort=()  
last-modified: Wed, 06 Mar 2024 01:36:34 GMT  
access-control-allow-origin: *  &rarr; This header indicates that the code on this domain can be executed in a browser from within another domain, which is a desirable feature to make the RDF data available on other domains.  
strict-transport-security: max-age=31556952  
etag: "65e7c8a2-c1d" &rarr; the ETag header is a unique value generated by the server, which the client can use to verify if the cached resource hasn't changed on the server (if so the server replies with status code 304).  
expires: Wed, 06 Mar 2024 02:09:25 GMT  
cache-control: max-age=600 &rarr; this is the maximum allowed age (in seconds - so, 10 minutes here) to use the cached resource.  
x-proxy-cache: MISS  
x-github-request-id: EDBA:331E65:47E307:495F5F:65E7CDFD  
accept-ranges: bytes  
date: Wed, 06 Mar 2024 01:59:25 GMT  
via: 1.1 varnish  
age: 0  
x-served-by: cache-bru1480044-BRU  
x-cache: MISS  
x-cache-hits: 0  
x-timer: S1709690366.684412,VS0,VE110  
vary: Accept-Encoding  
x-fastly-request-id: 180981ddd2b4a32f0ad6bac30f35f3e242b2690c  
content-length: 3101  
