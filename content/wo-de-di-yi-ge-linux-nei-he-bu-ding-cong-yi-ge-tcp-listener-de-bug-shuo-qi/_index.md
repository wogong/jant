---
id: "pst_01kt0kf5wff27skkfsv4dt79ww"
title: "我的第一个 Linux 内核补丁：从一个 TCP Listener 的 Bug 说起"
date: "2026-06-01T03:26:04.000Z"
slug: "wo-de-di-yi-ge-linux-nei-he-bu-ding-cong-yi-ge-tcp-listener-de-bug-shuo-qi"
type: "post"
format: "link"
status: "published"
visibility: "public"
summary_text: "Quote：但是一个长久运行的开源社区强调的是代码的可维护性，能够让许多维护者顺利完成接力跑。当然有人会说 LLM 自己写代码，LLM 自己维护自己修，嗯，我觉得这个观点我不想去辩驳。但我觉得，一个长期维护的项目这么搞，以 LLM 存在的随机性和上下文限制，没有一些拥有工程品味和真正长期记忆的维护者，最后的结局肯定是：迭代变得越来越困难，修一个 Bug 牵一发动全身，维护不下去之后然后开始漫漫重写/重构之路。"
link_url: "https://jt26wzz.com/posts/0016-my-first-linux-kernel-patch-fixing-a-tcp-listener-bug/"
---

Quote：但是一个长久运行的开源社区强调的是代码的可维护性，能够让许多维护者顺利完成接力跑。当然有人会说 LLM 自己写代码，LLM 自己维护自己修，嗯，我觉得这个观点我不想去辩驳。但我觉得，一个长期维护的项目这么搞，以 LLM 存在的随机性和上下文限制，没有一些拥有工程品味和真正长期记忆的维护者，最后的结局肯定是：迭代变得越来越困难，修一个 Bug 牵一发动全身，维护不下去之后然后开始漫漫重写/重构之路。
