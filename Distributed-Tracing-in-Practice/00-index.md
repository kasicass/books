# Distributed Tracing in Practice（分布式追踪实战）

原书：《Distributed Tracing in Practice》（O'Reilly，2020 年 4 月第一版）

---

## 这本书讲什么

软件一旦跑在多台机器上、拆成上百个服务，传统的 log 与 metrics 便只剩故事的一角——你知道「出了事」，却不知道「事出何因」。Distributed tracing 正是为这个时代补上的那双眼睛：它把一次请求在成百上千个服务之间的来龙去脉，还原成一条看得见、问得清的 trace。

本书不空谈概念，而是带你走完一条完整的路：从 instrumentation 的取舍，到部署与成本，再到 sampling、性能分析与未来演进。作者都是这一领域的当事人——Dapper 的联合创造者作序，Pivot Tracing 的作者执笔。他们讲的，是自己趟过的坑。

一句话：**这本书讲的是「为什么」与「怎么权衡」，不是一本贴 API 的手册。**

---

## 目录

### 序与引言

- [序](00-foreword.md) —— Ben Sigelman
- [引言：什么是 Distributed Tracing？](00-introduction.md)

### 原理与落地（第 1–7 章）

- [第 1 章　Distributed Tracing 的难题](01-the-problem-with-distributed-tracing.md)
- [第 2 章　插桩的本体论](02-an-ontology-of-instrumentation.md)
- [第 3 章　开源插桩：接口、库与框架](03-open-source-instrumentation-interfaces-libraries-and-frameworks.md)
- [第 4 章　插桩最佳实践](04-best-practices-for-instrumentation.md)
- [第 5 章　部署 Tracing](05-deploying-tracing.md)
- [第 6 章　开销、成本与采样](06-overhead-costs-and-sampling.md)
- [第 7 章　新的可观测性评分卡](07-a-new-observability-scorecard.md)

### 分析与未来（第 8–14 章）

- [第 8 章　改善基线性能](08-improving-baseline-performance.md)
- [第 9 章　恢复基线性能](09-restoring-baseline-performance.md)
- [第 10 章　到了吗？回顾与现状](10-the-past-and-present.md)
- [第 11 章　超越单个请求](11-beyond-individual-requests.md)
- [第 12 章　超越 Span](12-beyond-spans.md)
- [第 13 章　超越 Distributed Tracing](13-beyond-distributed-tracing.md)
- [第 14 章　Context Propagation 的未来](14-the-future-of-context-propagation.md)

### 附录

- [附录 A　2020 年前后的 Distributed Tracing 现状](15-appendix-a-the-state-of-distributed-tracing-circa-2020.md)
- [附录 B　OpenTelemetry 中的 Context Propagation](16-appendix-b-context-propagation-in-opentelemetry.md)

### 关于作者

- [关于作者](17-about-the-authors.md)
