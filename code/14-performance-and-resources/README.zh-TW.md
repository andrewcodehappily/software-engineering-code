# 第十四編　效能與資源使用法

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

## 條文索引

- [17001 — 量測優先](#article-17001)
- [17002 — 複雜度證據](#article-17002)
- [17003 — Benchmark 條件](#article-17003)
- [17004 — 記憶體所有權](#article-17004)
- [17005 — 過早 Optimization](#article-17005)
- [17006 — 平行程序](#article-17006)
- [17007 — Cache 費用](#article-17007)
- [17008 — Latency 分布](#article-17008)
- [17009 — 資源上限](#article-17009)
- [17010 — 能源統計](#article-17010)

<a name="article-17001"></a>

### 第 17001 條【量測優先】

Optimization 主張優於可讀程式碼前，應提出可量測之效益。

<a name="article-17002"></a>

### 第 17002 條【複雜度證據】

良好之漸近複雜度，不足以證明程式對法院目前所受理之 Input 執行快速。

<a name="article-17003"></a>

### 第 17003 條【Benchmark 條件】

以 Benchmark 結果宣告其他實作較差前，應揭露相關測試條件。

<a name="article-17004"></a>

### 第 17004 條【記憶體所有權】

程式不再需要之 Memory，不得僅以將來或許有用為由持續占有。

<a name="article-17005"></a>

### 第 17005 條【過早 Optimization】

從未出現於 Profile 之 Function，其加速工作不得當然列為緊急事項。

<a name="article-17006"></a>

### 第 17006 條【平行程序】

Worker Thread 數量增加者，不得推定有效 Throughput 等比例增加。

<a name="article-17007"></a>

### 第 17007 條【Cache 費用】

Cache 之評估除其節省之工作外，亦應包含使其失效之困難。

<a name="article-17008"></a>

### 第 17008 條【Latency 分布】

平均 Latency 符合要求者，不因此消滅最慢百分位使用者之申訴。

<a name="article-17009"></a>

### 第 17009 條【資源上限】

尚有 RAM 可用者，不構成耗盡全部 RAM 之授權。

<a name="article-17010"></a>

### 第 17010 條【能源統計】

程式較早完成工作者，未經量測不得當然認定其能源效率較高。
