# Part 9: Database Administration

[繁體中文](README.zh-TW.md) · [Section index](../README.md) · [Master index](../../README.md)

## Article Index

- [12001 — Null Status](#article-12001)
- [12002 — Transaction Integrity](#article-12002)
- [12003 — Migration Evidence](#article-12003)
- [12004 — Backup Testimony](#article-12004)
- [12005 — Index Economics](#article-12005)
- [12006 — N Plus One](#article-12006)
- [12007 — Schema Authority](#article-12007)
- [12008 — Time Zone Evidence](#article-12008)
- [12009 — Pagination Order](#article-12009)
- [12010 — Production Data](#article-12010)

<a name="article-12001"></a>

### Article 12001 — Null Status

NULL shall not be presumed equal to zero, an empty string, or a developer's optimism.

<a name="article-12002"></a>

### Article 12002 — Transaction Integrity

A partially completed transaction shall not be declared successful on the grounds that most of it worked.

<a name="article-12003"></a>

### Article 12003 — Migration Evidence

The existence of a migration script shall not constitute proof that it can be safely executed against production data.

<a name="article-12004"></a>

### Article 12004 — Backup Testimony

A backup whose restoration has never been tested shall be regarded as a witness not yet cross-examined.

<a name="article-12005"></a>

### Article 12005 — Index Economics

Every proposed index shall acknowledge both the queries it accelerates and the writes it burdens.

<a name="article-12006"></a>

### Article 12006 — N Plus One

A query that secretly issues one request per row shall disclose its accomplices before claiming innocence.

<a name="article-12007"></a>

### Article 12007 — Schema Authority

Where the diagram and the live schema disagree, the diagram shall be summoned for questioning.

<a name="article-12008"></a>

### Article 12008 — Time Zone Evidence

A timestamp without sufficient time zone context shall not be accepted as decisive evidence of chronological order.

<a name="article-12009"></a>

### Article 12009 — Pagination Order

Pagination without a stable ordering shall not guarantee that a citizen appears on precisely one page.

<a name="article-12010"></a>

### Article 12010 — Production Data

The words test data shall not be applied to production records merely to make an experiment appear harmless.
