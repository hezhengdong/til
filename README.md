# TIL

## 2026-05-23

AI 如何影响程序员？我的理解是什么？

1. cursor ceo 的这段话不错，我还记得最开始卖点是 tab，后来 cc 赶超。[link](https://x.com/mntruell/status/2026736314272591924)
2. gitlab 的文章不错，指出了明确的未来。[link](https://about.gitlab.com/blog/gitlab-act-2/)
3. karpathy 的帖子，有段话很认同。[link](https://x.com/karpathy/status/2026731645169185220?s=20)
4. 团队的 leader 和成员，leader 要能够容忍成员干自己轻松干完的事情。[link](https://www.zhihu.com/question/657500142/answer/2025520612798473148)

将这四个论点联系在一起，就是自己目前的认知了：

编码分为负责任和不负责任

- 对于负责任的编码
    - 学新东西的时候，最好纯手动编码。如果偷懒交给 llm，还是需要仔细查看 llm 的内容，直到自己完全理解。
    - 对于自己已经非常熟悉的部分，那就大胆交给 llm，随后直接 review，就像 github 协作那样。

- 如果自用，那就不负责任的 vide coding 吧。

不过，还有一种说法是，vibe coding 与 agentic engineering 似乎并没有那么泾渭分明

https://x.com/karpathy/status/2019137879310836075

https://simonwillison.net/2026/May/6/vibe-coding-and-agentic-engineering/

但自己潜意识里还是认为 vibe coding 和 agentic engineering 是泾渭分明的，因为即便的不 review 的 vide coding，比如 bun 用 rust 重写，还是经过了所有测试的。

另外，karpathy 有个 llm.c，没想到还有 java 版本和 go 版本，自己感兴趣的时候可以看看。