# 第九編　資料庫管理法

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

## 條文索引

- [12001 — NULL 之法律地位](#article-12001)
- [12002 — 交易完整性](#article-12002)
- [12003 — Migration 證據](#article-12003)
- [12004 — 備份證詞](#article-12004)
- [12005 — Index 經濟法](#article-12005)
- [12006 — N+1 案件](#article-12006)
- [12007 — Schema 效力](#article-12007)
- [12008 — 時區證據](#article-12008)
- [12009 — 分頁秩序](#article-12009)
- [12010 — Production 資料保護](#article-12010)

<a name="article-12001"></a>

### 第 12001 條【NULL 之法律地位】

NULL 不得推定等於零、空字串或開發者之樂觀期待。

<a name="article-12002"></a>

### 第 12002 條【交易完整性】

Transaction 僅部分完成者，不得以大部分已成功為由宣告完成。

<a name="article-12003"></a>

### 第 12003 條【Migration 證據】

Migration Script 之存在，不足以證明其得安全套用於 Production 資料。

<a name="article-12004"></a>

### 第 12004 條【備份證詞】

未曾驗證還原之備份，視為尚未接受交互詰問之證人。

<a name="article-12005"></a>

### 第 12005 條【Index 經濟法】

新增 Index 者，應同時考量其加速之查詢及增加負擔之寫入。

<a name="article-12006"></a>

### 第 12006 條【N+1 案件】

每筆資料暗中另行發出查詢之 Query，主張無罪前應揭露其共犯。

<a name="article-12007"></a>

### 第 12007 條【Schema 效力】

資料庫示意圖與實際 Schema 不符者，應傳喚示意圖接受調查。

<a name="article-12008"></a>

### 第 12008 條【時區證據】

欠缺充分時區資訊之 Timestamp，不得作為事件先後順序之決定性證據。

<a name="article-12009"></a>

### 第 12009 條【分頁秩序】

欠缺穩定排序之分頁，不得保證每筆資料僅出現於一頁。

<a name="article-12010"></a>

### 第 12010 條【Production 資料保護】

不得僅為使實驗看似無害，而將 Production 資料稱為測試資料。
