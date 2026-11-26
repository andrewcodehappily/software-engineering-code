# 第 009 號：兩個等待中的 Thread 案

[English](README.md) · [返回上層](../README.zh-TW.md) · [總目錄](../../README.zh-TW.md)

> 虛構示範判例，非真實 GitHub 案件或法律判決。

## 事實

兩個 Thread 各持有對方所需之 Lock，雙方均向 Scheduler 請求救濟。

## 判決理由

依第 26002 條應調查 Locking Protocol。單純增加排程機會不足以保證解除循環等待。

## 主文

本案移送 Lock Order Review。不得要求任一 Thread 等待對方寫完上訴書。
