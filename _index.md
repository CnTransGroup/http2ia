+++
title = "http2ia"
template = "http2ia_section.html"
sort_by = "weight"
paginate_by = 100
weight = 997
+++

《HTTP/2 in action》翻译学习

## 目录：

[1. Web 技术与 HTTP](part1.moving_to_http2/1-web-technologies-and-http)

[2. 总览 HTTP/2@todo](part1.moving_to_http2/2-the-road-to-http2)

[3. 升级到 HTTP/2@todo](part1.moving_to_http2/3-upgrading-to-http2)

[4. HTTP2 协议的基本元素@todo](part2.using_http2/4-http2-protocol-basics)

[5. 实现 HTTP/2 的 PUSH@todo](part2.using_http2/5-implementing-http2-push)

[6. HTTP/2 的优化@todo](part2.using_http2/6-optimizing-for-http2)

[7. HTTP/2 的高级概念@todo](part3.advanced_http2/7-advanced-http2-concepts)

[8. HPACK 压缩 Header@todo](part3.advanced_http2/8-hpack-hearder-compression)

[9. TCP、QUIC 和 HTTP/3@doing](part4.the_future_of_http/9-tcp-quic-and-http3)

[10. HTTP 去向何方@todo](part4.the_future_of_http/10-where-http-goes-from-here)

## 其他

### Parser
[http-parser](https://github.com/nodejs/http-parser)
这个解析库在2019年已经停止，原因是作者觉得这个库已经难以维护，转为使用
[llhttp](https://github.com/nodejs/llhttp)
使用 TypeScript 编写，生成 C 代码，benchmark 显示生成的 C 代码运行比 http-parser 更快

## 法律声明

译者纯粹出于**学习目的**与**个人兴趣**翻译本书，不追求任何经济利益。

译者保留对此版本译文的署名权，其他权利以原作者和出版社的主张为准。

本译文只供学习研究参考之用，不得公开传播发行或用于商业用途。有能力阅读英文书籍者请购买正版支持。
