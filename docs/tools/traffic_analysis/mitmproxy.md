# mitmproxy

**mitmproxy** is an interactive HTTPS proxy that allows you to intercept, modify and replay HTTP/S traffic.  It supports reverse proxying, transparent proxying and even WebSockets.

**Features:**

- View and edit requests and responses in real time.  
- Create replayable flows for testing.  
- Scriptable with Python for automated manipulation.  

**When to use:** when testing web and mobile applications to see and modify encrypted traffic or to simulate malicious proxies.

**Quickstart:**

```bash
mitmproxy -p 8080
```

Configure your browser or device to use `localhost:8080` as the HTTP/S proxy.  Use the interactive console to inspect flows.
