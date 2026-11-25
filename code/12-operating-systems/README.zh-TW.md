# 第十二編　作業系統管理法

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

## 條文索引

- [15001 — Exit Status 效力](#article-15001)
- [15002 — Process 身分](#article-15002)
- [15003 — 權限救濟](#article-15003)
- [15004 — 工作目錄](#article-15004)
- [15005 — Shell 管轄](#article-15005)
- [15006 — 隱藏文件](#article-15006)
- [15007 — Signal 程序](#article-15007)
- [15008 — 環境繼承](#article-15008)
- [15009 — 磁碟容量](#article-15009)
- [15010 — Uptime 特權](#article-15010)

<a name="article-15001"></a>

### 第 15001 條【Exit Status 效力】

未產生 Output 之 Command，於取得其他證據前不得推定成功或失敗。

<a name="article-15002"></a>

### 第 15002 條【Process 身分】

名稱相同之 Process，不得推定為同一 Process。

<a name="article-15003"></a>

### 第 15003 條【權限救濟】

Permission denied 不當然構成申請無限制權限之依據。

<a name="article-15004"></a>

### 第 15004 條【工作目錄】

相對路徑應依實際 Working Directory 解釋，不問作者原欲立足何處。

<a name="article-15005"></a>

### 第 15005 條【Shell 管轄】

某 Shell 所接受之語法，不當然為其他具有獨立主權之 Shell 所承認。

<a name="article-15006"></a>

### 第 15006 條【隱藏文件】

名稱以點開頭之文件，不因此免受儲存統計或版本控制審查。

<a name="article-15007"></a>

### 第 15007 條【Signal 程序】

Process 經要求終止者，於情況許可時應給予清理資源之機會。

<a name="article-15008"></a>

### 第 15008 條【環境繼承】

Interactive Shell 可見之變數，不得推定所有背景服務皆可見。

<a name="article-15009"></a>

### 第 15009 條【磁碟容量】

以十進位單位標示之磁碟，不因二進位單位顯示不同數字而受起訴。

<a name="article-15010"></a>

### 第 15010 條【Uptime 特權】

長期 Uptime 得證明持續運行之能力，但不得證明 Bug 不存在。
