# Part 18: Compiler and Build Law

[繁體中文](README.zh-TW.md) · [Section index](../README.md) · [Master index](../../README.md)

## Article Index

- [21001: Compiler testimony](#article-21001)
- [21002: Missing semicolon](#article-21002)
- [21003: Clean build](#article-21003)
- [21004: Linker jurisdiction](#article-21004)
- [21005: Build duration](#article-21005)
- [21006: Parallel jobs](#article-21006)
- [21007: Warning appeal](#article-21007)
- [21008: Debug and release](#article-21008)
- [21009: Build cache](#article-21009)
- [21010: Target architecture](#article-21010)
- [21011: Compiler flags](#article-21011)
- [21012: Build reproducibility](#article-21012)

<a name="article-21001"></a>

### Article 21001 — Compiler testimony

A diagnostic pointing to line 80 shall not establish that line 80 committed the offense.

<a name="article-21002"></a>

### Article 21002 — Missing semicolon

A missing semicolon may be responsible for a subsequent uprising of diagnostics, none of which shall be counted as independent offenses.

<a name="article-21003"></a>

### Article 21003 — Clean build

A clean build may be ordered when incremental build artifacts contradict the source record.

<a name="article-21004"></a>

### Article 21004 — Linker jurisdiction

Successful compilation of every translation unit shall not bind the linker to a favorable judgment.

<a name="article-21005"></a>

### Article 21005 — Build duration

An engineer awaiting a build shall not be required to start another build merely to demonstrate productivity.

<a name="article-21006"></a>

### Article 21006 — Parallel jobs

The number of build jobs shall be determined by available resources, not by the largest integer accepted by the command line.

<a name="article-21007"></a>

### Article 21007 — Warning appeal

A warning newly introduced by a toolchain upgrade shall be examined before being attributed to a change in application behavior.

<a name="article-21008"></a>

### Article 21008 — Debug and release

A program acquitted in debug mode may still be summoned for trial in release mode.

<a name="article-21009"></a>

### Article 21009 — Build cache

A cached artifact shall not testify that the current source was compiled unless its provenance supports that claim.

<a name="article-21010"></a>

### Article 21010 — Target architecture

An executable shall not acquire citizenship on another architecture merely by being copied there.

<a name="article-21011"></a>

### Article 21011 — Compiler flags

A flag added by trial and error shall be documented before its original purpose disappears from collective memory.

<a name="article-21012"></a>

### Article 21012 — Build reproducibility

The existence of a binary on one engineer's desktop shall not establish a reproducible build procedure.
