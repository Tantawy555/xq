# XQ
XQ (pronounced as "clock") is a high-efficiency federation protocol for microblogging.

- Use Protocol Buffers to make messages as small as possible by communicating in a completely pre-defined format.
- Eliminate unnecessary data and boilerplate by focusing on microblogging for its intended use.
  - If it proves to be scalable for other purposes without compromising efficiency, it may be possible to support use cases other than microblogging.

Note that this protocol is intended to be used primarily for Misskey-to-Misskey communication for efficiency, but any software with a similar concept to Misskey should be able to use it.
