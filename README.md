# Config files and scripts for HAProxy 1.8 with HTTP/2 and dynamic reconfiguration

An 'haproxy.cfg' with :

 - Logging to systemd
 - The various www vs non-www, HTTP vs HTTPS combinations redirected to a single HTTPS site.
 - The ability to switch backends dynamically
 - HTTP/2 support in all browsers
 - A branded 'sorry' page
 - A separate server that handles blogs and marketing content
 - Support for [HTML5 Server Sent Events](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events)
 - An A+ on the SSL Labs test

See the [full docs](https://certsimple.com/blog/haproxy-http2-dynamic-load-balancing-ssl) at [fast EV HTTPS verification](https://certsimple.com) provider [CertSimple](https://certsimple.com).
