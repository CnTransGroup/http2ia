+++
title = "http2ia"
template = "http2ia_section.html"
sort_by = "weight"
paginate_by = 100
weight = 997
+++

《HTTP/2 in action》翻译学习

#### 目录：

> Part1
>
> 要理解 HTTP/2 为何在 Web 性能领域中引起轰动，首先要了解有什么问题需要解决和为什么需要它。因此，本书的第一部分就向那些不熟悉 HTTP/1 的读者介绍 HTTP/1；然后阐述为什么需要 HTTP/2。从一个较高的层面讨论 HTTP/2 如何工作，低层面的细节留在本书的后面部分再讨论。相反，通过讨论如何将 HTTP/2 部署到你的站点来结束本部分。

[1. Web 技术与 HTTP](part1.moving_to_http2/1.web_technologies_and_http.md)

[2. 总览 HTTP/2@todo](part1.moving_to_http2/2.the_road_to_http2.md)

[3. 升级到 HTTP/2@todo](part1.moving_to_http2/3.upgrading_to_http2.md)

> Part2
>
> 在本书的第一部分，我介绍了 HTTP/2 的需要和动机，介绍了 HTTP/2 本身，描述了如何在你的站点部署 HTTP/2。对很多人来说，这些信息就足够了，即使不做任何改变升级到 HTTP/2 也能获得回报。HTTP/2 的设计易于迁移到大多数站点，并为它们带来了直接好处，而无需任何更改。
>
> 为了真正受益于 HTTP/2 所提供的所有功能，对协议及其工作原理有更深入的理解是很有用的。本书的这部分描述的协议核心的方方面面。第 4 和第 5 章覆盖了网站拥有者和开发利用 HTTP/2 协议的技术细节。第 6 章从协议本身触发，讨论了对 Web 性能的意义以及开发人员针对 HTTP/2 如何优化。

[4. HTTP2 协议的基本元素@todo](part2.using_http2/4.http2_protocol_basics.md)

[5. 实现 HTTP/2 的 PUSH@todo](part2.using_http2/5.implementing_http2_push.md)

[6. HTTP/2 的优化@todo](part2.using_http2/6.optimizing_for_http2.md)

> Part3 
>
> 本书的第一部分介绍了 HTTP/2。第二部分了解了 HTTP/2 的细节以及如何使用。第 4 章介绍了 HTTP/2 的基本概念以及如何工作；第 5 章描述了 HTTP/2 的 PUSH，对于 HTTP 来说一个新的概念；第 6 章研究了 HTTP/2 应该或者不应该改变开发的实践。
>
> 本部分，继续更深入的探究，介绍一些鲜为人知的高级主题。第 7 章完成了规范中之前未涉及的部分，第 8 章单独介绍了 HPACK HTTP 头部压缩规范。这两章将帮助你从基础使用者转变为 HTTP/2 协议的专家。你将能解决任何 HTTP/2 的问题，甚至可以为不断发展的协议作出贡献。

[7. HTTP/2 的高级概念@todo](part3.advanced_http2/7.advanced_http2_concepts.md)

[8. HPACK 压缩 Header@todo](part3.advanced_http2/8.hpack_hearder_compression.md)

> Part4
>
> 到了这里，你应该对于 HTTP/2 有了深入的理解并完全了解了规范。在这最后的部分，我们来讨论一下 HTTP 的未来。HTTP/2 被越来越多的网站所使用，但是帮助定义 Internet 协议的人并没有为此感到骄傲。在某些方面，HTTP/2 是个老新闻，人们已经开始关注下一代改进的协议。
>
> 第 9 章介绍 QUIC。QUIC 是一种新协议，旨在继续 HTTP/2 的工作，并解决 TCP 层的问题。即将进行标准化（本书出版时可能已经标准化了），但是我猜测广泛使用可能需要更长的时间。QUIC 使用了 HTTP/2 的许多概念，因此读者应该可以很容易开始学习该协议，并可能很快用起来。
>
> 返回协议层，第 10 章，我继续讨论 HTTP 可能的演化。HTTP 已经很健壮并可扩展，HTTP/2 延续了这良好的传统，同时有很多选择可以使协议更进一步。

[9. TCP、QUIC 和 HTTP/3@doing](part4.the_future_of_http/9.tcp_quic_and_http3.md)

[10. HTTP 去向何方@todo](part4.the_future_of_http/10.where_http_goes_from_here.md)

## 法律声明

译者纯粹出于**学习目的**与**个人兴趣**翻译本书，不追求任何经济利益。

译者保留对此版本译文的署名权，其他权利以原作者和出版社的主张为准。

本译文只供学习研究参考之用，不得公开传播发行或用于商业用途。有能力阅读英文书籍者请购买正版支持。
