# node-websockify-module
Modification of websockify (https://github.com/kanaka/websockify/tree/master/other/js) to allow for use as a module

Example Usage:

var websockify = require("websockify");

var proxy = websockify({source: ":8000", target: "192.168.1.10:5900"}); // listening on port 8000, connecting to VNC server running on 192.168.1.10