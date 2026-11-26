# 第 007 號：編譯器警告案

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

> 虛構示範判例，非真實 GitHub 案件或法律判決。

## 事實

某次 Build 帶著大量 Warning 完成，工程師援引第 4097 條，惟後續 Review 發現其中涉及 Undefined Behavior。

## 判決理由

本條允許暫予忽略一般 Warning，但明文排除之警告不在此限。編譯成功不足以證明執行安全。

## 主文

一般 Warning 暫予放行；涉及 Undefined Behavior 者發回調查。編譯器不因已提出警告而負責。
