# proxy

Walkthrough:
walkthrough.gif

Configuration:

CLI Arguments:

The following CLI arguments are supported:

--host

The host of the destination server. Defaults to 127.0.0.1.

--port

The port of the destination server. Defaults to 80 or 8000 when a host is not specified.

--url

A single url that overrides the above. E.g., http://www.google.com

--logfile

Specify a file path to redirect logging to.

Headers

The follow http header(s) are supported:

x-destination-url

Specify the destination url on a per request basis. Overrides and follows the same format as the --url argument. But also requires the port for example:
google.com:80
127.0.0.1:8000
