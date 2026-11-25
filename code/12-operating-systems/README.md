# Part 12: Operating Systems

[繁體中文](README.zh-TW.md) · [Section index](../README.md) · [Master index](../../README.md)

## Article Index

- [15001 — Exit Status](#article-15001)
- [15002 — Process Identity](#article-15002)
- [15003 — Permission Appeals](#article-15003)
- [15004 — Working Directory](#article-15004)
- [15005 — Shell Jurisdiction](#article-15005)
- [15006 — Hidden Files](#article-15006)
- [15007 — Signal Proceedings](#article-15007)
- [15008 — Environment Inheritance](#article-15008)
- [15009 — Disk Capacity](#article-15009)
- [15010 — Uptime Privilege](#article-15010)

<a name="article-15001"></a>

### Article 15001 — Exit Status

A command producing no output shall not be presumed either successful or unsuccessful without further evidence.

<a name="article-15002"></a>

### Article 15002 — Process Identity

Processes sharing a name shall not be presumed to be the same process.

<a name="article-15003"></a>

### Article 15003 — Permission Appeals

Permission denied shall not automatically authorize a request for unlimited privileges.

<a name="article-15004"></a>

### Article 15004 — Working Directory

A relative path shall be interpreted according to the actual working directory, regardless of where the author intended to stand.

<a name="article-15005"></a>

### Article 15005 — Shell Jurisdiction

Syntax accepted by one shell shall not automatically be recognized by another sovereign shell.

<a name="article-15006"></a>

### Article 15006 — Hidden Files

A file whose name begins with a dot shall not be exempt from storage accounting or version control review.

<a name="article-15007"></a>

### Article 15007 — Signal Proceedings

A process requested to terminate shall be afforded an opportunity to clean up where circumstances permit.

<a name="article-15008"></a>

### Article 15008 — Environment Inheritance

A variable visible in an interactive shell shall not automatically be presumed visible to every background service.

<a name="article-15009"></a>

### Article 15009 — Disk Capacity

A disk advertised in decimal units shall not be prosecuted for failing to contain the same numeral in binary units.

<a name="article-15010"></a>

### Article 15010 — Uptime Privilege

A long uptime shall be admitted as evidence of endurance, but not of the absence of bugs.
