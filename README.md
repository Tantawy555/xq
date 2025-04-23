# XQ
XQ (pronounced as "clock") is a high-efficiency federation protocol for microblogging.

- Using Protocol Buffers, which are in binary format, allows communication to be in a format with a fully pre-defined schema, making the message as small as possible.
- Eliminate unnecessary data and boilerplate by focusing on microblogging for its intended use.
  - If it proves to be scalable for other purposes without compromising efficiency, it may be possible to support use cases other than microblogging.
- Allows multiple messages to be combined into a single request to reduce overhead.

Note that this protocol is intended to be used primarily for Misskey-to-Misskey communication for efficiency, but any software with a similar concept to Misskey should be able to use it.
