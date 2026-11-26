# 第二十三編　Concurrency 與分散式系統法

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

## 條文索引

- [26001: 競態案件](#article-26001)
- [26002: Deadlock](#article-26002)
- [26003: 時鐘爭議](#article-26003)
- [26004: Network Partition](#article-26004)
- [26005: 重複傳遞](#article-26005)
- [26006: Queue 積案](#article-26006)
- [26007: Eventual Consistency](#article-26007)
- [26008: 取消程序](#article-26008)
- [26009: Backpressure](#article-26009)
- [26010: Distributed Tracing](#article-26010)
- [26011: Leader 選舉](#article-26011)
- [26012: 部分故障](#article-26012)

<a name="article-26001"></a>

### 第 26001 條【競態案件】

兩個 Thread 以非預期順序抵達者，不得推定違反從未受保證之排程。

<a name="article-26002"></a>

### 第 26002 條【Deadlock】

互相等待對方許可之當事方，得命檢查 Locking Protocol，不得永久等待司法介入。

<a name="article-26003"></a>

### 第 26003 條【時鐘爭議】

單一 Node 之時鐘不得當然推翻其他 Node 對事件順序之紀錄。

<a name="article-26004"></a>

### 第 26004 條【Network Partition】

無法聯繫其他 Node 者，不得推定其餘 Node 全部消失。

<a name="article-26005"></a>

### 第 26005 條【重複傳遞】

重複收到 Message 者，不得當然授權執行兩次不可逆業務操作。

<a name="article-26006"></a>

### 第 26006 條【Queue 積案】

Queue 不因所有新 Message 均成功進入持續增加之積案即視為健康。

<a name="article-26007"></a>

### 第 26007 條【Eventual Consistency】

Eventual 一詞非有額外保證，不得解讀為精確契約時間。

<a name="article-26008"></a>

### 第 26008 條【取消程序】

Caller 已取消者，不足以證明遠端操作亦已取消。

<a name="article-26009"></a>

### 第 26009 條【Backpressure】

Producer 應尊重 Consumer 之容量，不得將其耗盡資源轉化為未記載功能。

<a name="article-26010"></a>

### 第 26010 條【Distributed Tracing】

可行時 Trace ID 應隨相關 Request 傳遞，以免法院須藉占星重建其旅程。

<a name="article-26011"></a>

### 第 26011 條【Leader 選舉】

Node 自行宣告為 Leader 者，非有 Protocol 所需證據，不得證明其具有排他權限。

<a name="article-26012"></a>

### 第 26012 條【部分故障】

單一 Component 存活者，不構成宣告整體分散式系統健康之授權。
