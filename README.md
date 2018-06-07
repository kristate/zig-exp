# zig-exp
`exp`: The Experimental Standard Library for [Zig](http://ziglang.org/)

## How to use

First retrieve the repo:
```
cd your_project
git clone https://github.com/kristate/zig-exp.git exp
```

And then import from within your Zig project:

```zig
const exp = @import("exp");
```

## Standard Modules

`exp` will first focus on support for the following features and modules:

| Name     | Status   | Description                                    |
|----------|----------|------------------------------------------------|
| base64   | unstable | Base-64 encoding/decoding functions            |
| conf     | unstable | Configuration file parser                      |
| crc32    | unstable | 32-bit CRC defined in ITU V.42                 |
| crypto   | unstable | Cryptographic Primitives                       |
| dbg      | unstable | Debug printing                                 |
| dns      | unstable | DNS resolving (NAPTR, SRV, A)                  |
| fmt      | unstable | Formatted printing and regular expression      |
| hash     | unstable | HashMap Implementation                         |
| http     | unstable | HTTP parser (RFC 2616)                         |
| httpauth | unstable | HTTP-based Authentication (RFC 2617)           |
| json     | unstable | JavaScript Object Notation (JSON)              |
| list     | unstable | Sortable doubly-linked list handling           |
| lock     | unstable | Resource locking functions                     |
| loop     | unstable | Main poll loop                                 |
| mbuf     | unstable | Linear memory buffers                          |
| mem      | unstable | Memory referencing                             |
| mod      | unstable | Run-time module loading                        |
| mqueue   | unstable | Thread-safe message queue                      |
| net      | unstable | Networking routines                            |
| odict    | unstable | Ordered Dictionary                             |
| platform | unstable | Platform Specific Functions and Primatives     |
| sa       | unstable | Socket Address functions                       |
| sys      | unstable | System information                             |
| tcp      | unstable | TCP transport                                  |
| tls      | unstable | Transport Layer Security                       |
| tmr      | unstable | Timer handling                                 |
| udp      | unstable | UDP transport                                  |
| uri      | unstable | Generic URI library                            |
| websock  | unstable | WebSocket Client and Server                    |

