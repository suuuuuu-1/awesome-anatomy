# Connection pool

[← Prompt index](index.md) · [中文索引](index.zh-CN.md) · [Gallery](../README.md)

**Creator / 作者:** Abhay Kumar

[Original work / 原作](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs#L20) · [Published prompt source / 提示词出处](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs)

3 tools represent reusable connections. Each job borrows a tool for 3 seconds, and up to 4 jobs can wait in a first-in, first-out queue.

用共享工具架解释连接借用、排队与容量上限。

## Published prompt / 公开提示词

Author-published text; completeness and reproduction have not been independently established. / 作者公开文本，未独立确认是否包含全部修改过程或可直接复现。

```text
Explain a connection pool as a rack of 3 reusable tools. Jobs take 3 seconds, 4 jobs can wait FIFO, and excess requests are rejected. Add manual return controls, a 1-second clock step, and job IDs so I can follow handoffs. Deliver standalone HTML.
```

## Resources / 相关资料

[Original](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs#L20) · [Code](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/models.mjs)

## Attribution / 署名

MIT by Abhay Kumar; original notice retained in docs/licenses/cutaway-MIT.txt

The prompt remains under its original terms; the catalog’s CC0 dedication does not relicense it. See [source notices](../docs/THIRD_PARTY.md).
