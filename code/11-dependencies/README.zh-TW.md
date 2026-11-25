# 第十一編　套件與依賴管理法

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

## 條文索引

- [14001 — 依賴入籍](#article-14001)
- [14002 — Lockfile 效力](#article-14002)
- [14003 — 版本範圍](#article-14003)
- [14004 — 套件失聯](#article-14004)
- [14005 — 安裝程序](#article-14005)
- [14006 — 依賴廢止](#article-14006)
- [14007 — 零版地位](#article-14007)
- [14008 — 名稱辨識](#article-14008)
- [14009 — 升級聽證](#article-14009)
- [14010 — Vendor 檔案](#article-14010)

<a name="article-14001"></a>

### 第 14001 條【依賴入籍】

為解決單一小問題而安裝之 Package，可能攜帶大量須登記之間接依賴。

<a name="article-14002"></a>

### 第 14002 條【Lockfile 效力】

已 Commit 之 Lockfile，不因包含大量陌生名稱而視為裝飾文件。

<a name="article-14003"></a>

### 第 14003 條【版本範圍】

允許安裝較新版本者，不足以證明其具有相容性。

<a name="article-14004"></a>

### 第 14004 條【套件失聯】

長期未維護之 Package，應依其實際狀況評估，不得僅依最後 Commit 日期判定。

<a name="article-14005"></a>

### 第 14005 條【安裝程序】

Install Script 所受信任，不得高於直接執行之同等 Script。

<a name="article-14006"></a>

### 第 14006 條【依賴廢止】

廢止 Dependency 前，應查明或合理排除仍使用該依賴之程式。

<a name="article-14007"></a>

### 第 14007 條【零版地位】

版本號為 0 之 Package，不因其版本號而免除部署至 Production 之後果。

<a name="article-14008"></a>

### 第 14008 條【名稱辨識】

僅與可信 Package 名稱相差一字元者，不因此繼承原套件之信任。

<a name="article-14009"></a>

### 第 14009 條【升級聽證】

標示為 Minor 之升級，仍得傳喚至 Integration Test 接受審查。

<a name="article-14010"></a>

### 第 14010 條【Vendor 檔案】

Vendor Code 縱為匯入者所遺忘，仍應保留其來源與授權資訊。
