# Circuit breaker

[← Prompt index](index.md) · [中文索引](index.zh-CN.md) · [Gallery](../README.md)

**Creator / 作者:** Abhay Kumar

[Original work / 原作](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs#L29) · [Published prompt source / 提示词出处](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs)

The relay stops traffic after 3 consecutive failures. After a 5-second cooldown, it allows 1 trial request to check whether the service has recovered.

用安全开关解释熔断器在故障和恢复期间的状态变化。

## Published prompt / 公开提示词

Author-published text; completeness and reproduction have not been independently established. / 作者公开文本，未独立确认是否包含全部修改过程或可直接复现。

```text
Build a circuit breaker as an isometric safety relay. Trip after 3 consecutive failures, cool down for 5 seconds, then allow 1 half-open probe. Let me fail or restore the downstream service and resolve the probe separately. Deliver standalone HTML with state and rejection readouts.
```

## Resources / 相关资料

[Original](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/catalog.mjs#L29) · [Code](https://github.com/abhay/cutaway/blob/abc8f7af1941d4e724d854a9c1c32905cbe240f3/skills/cutaway/examples/models.mjs)

## Attribution / 署名

MIT by Abhay Kumar; original notice retained in docs/licenses/cutaway-MIT.txt

The prompt remains under its original terms; the catalog’s CC0 dedication does not relicense it. See [source notices](../docs/THIRD_PARTY.md).
