# Token bucket

[← Prompt index](index.md) · [中文索引](index.zh-CN.md) · [Gallery](../README.md)

**Creator / 作者:** Abhay Kumar

[Original work / 原作](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs#L2) · [Published prompt source / 提示词出处](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs)

The dispenser stores up to 10 tokens. Each accepted request spends 1 token, and the clock adds 2 tokens per second.

用机械代币分发器解释令牌桶容量、补充速率和突发请求。

## Published prompt / 公开提示词

Author-published text; completeness and reproduction have not been independently established. / 作者公开文本，未独立确认是否包含全部修改过程或可直接复现。

```text
Explain a token bucket rate limiter as a mechanical token dispenser. Use a capacity of 10, a refill rate of 2 tokens per second, and a cost of 1 token per request. Add a burst of 11, a paused clock with 1-second steps, live accepted/rejected totals, and a standalone HTML file.
```

## Resources / 相关资料

[Original](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs#L2) · [Code](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/models.mjs)

## Attribution / 署名

MIT by Abhay Kumar; original notice retained in docs/licenses/cutaway-MIT.txt

The prompt remains under its original terms; the catalog’s CC0 dedication does not relicense it. See [source notices](../docs/THIRD_PARTY.md).
