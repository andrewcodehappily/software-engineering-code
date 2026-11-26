# SEC Case 009: The Two Waiting Threads

[繁體中文](README.zh-TW.md) · [Section index](../README.md) · [Master index](../../README.md)

> Fictional illustrative precedent, not an actual GitHub case or legal judgment.

## Facts

Two threads each held a lock required by the other. Both petitioned the scheduler for assistance.

## Reasoning

Under Article 26002, the locking protocol must be examined. Additional scheduling opportunities alone cannot guarantee resolution of a circular wait.

## Disposition

The matter is referred for lock-order review. Neither thread shall be required to wait for the other to finish writing its appeal.
