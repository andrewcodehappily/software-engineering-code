# Part 23: Concurrency and Distributed Systems

[繁體中文](README.zh-TW.md) · [Section index](../README.md) · [Master index](../../README.md)

## Article Index

- [26001: Race conditions](#article-26001)
- [26002: Deadlock](#article-26002)
- [26003: Clock disagreement](#article-26003)
- [26004: Network partitions](#article-26004)
- [26005: Duplicate delivery](#article-26005)
- [26006: Queue backlogs](#article-26006)
- [26007: Eventual consistency](#article-26007)
- [26008: Cancellation](#article-26008)
- [26009: Backpressure](#article-26009)
- [26010: Distributed tracing](#article-26010)
- [26011: Leader elections](#article-26011)
- [26012: Partial failure](#article-26012)

<a name="article-26001"></a>

### Article 26001 — Race conditions

Two threads arriving in an unexpected order shall not be presumed to have violated a schedule that was never guaranteed.

<a name="article-26002"></a>

### Article 26002 — Deadlock

Parties mutually awaiting each other's permission may be ordered to review the locking protocol rather than wait for judicial intervention forever.

<a name="article-26003"></a>

### Article 26003 — Clock disagreement

A wall clock on one node shall not automatically overrule every other node's account of event ordering.

<a name="article-26004"></a>

### Article 26004 — Network partitions

A node unable to contact its peers shall not presume that all of them have ceased to exist.

<a name="article-26005"></a>

### Article 26005 — Duplicate delivery

A message received twice shall not automatically authorize two irreversible business operations.

<a name="article-26006"></a>

### Article 26006 — Queue backlogs

A queue shall not be deemed healthy merely because every new message is successfully accepted into its growing backlog.

<a name="article-26007"></a>

### Article 26007 — Eventual consistency

The term eventual shall not be interpreted as a precise contractual timestamp without additional guarantees.

<a name="article-26008"></a>

### Article 26008 — Cancellation

Cancellation of a caller shall not prove that its remote operation has also been cancelled.

<a name="article-26009"></a>

### Article 26009 — Backpressure

A producer shall respect the capacity of its consumers rather than converting their exhaustion into an undocumented feature.

<a name="article-26010"></a>

### Article 26010 — Distributed tracing

A trace identifier shall travel with the relevant request wherever practical, so the court need not reconstruct the journey by astrology.

<a name="article-26011"></a>

### Article 26011 — Leader elections

A node declaring itself leader shall not establish exclusive authority without the protocol's required evidence.

<a name="article-26012"></a>

### Article 26012 — Partial failure

The survival of one component shall not authorize a declaration that the entire distributed system is healthy.
