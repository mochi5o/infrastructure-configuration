# <Release Title> (<date>)

![architecture](./<same-name-directory>/diagram.png)

---

## What Changed
ユーザー・システム観点での変更点

---

## Constraints
この構成を選ばざるを得なかった制約

- downtime不可
- 既存DB共用
- DNS TTL制約
など

---

## Key Decisions

### <Decision title>
**Why**
なぜ必要だったか

**Alternative**
採用しなかった案

**Tradeoff**
失ったもの / 新たなリスク

---

### <Decision title>
（繰り返し）

---

## Risk Considerations
想定していた事故と回避策

- cache汚染 → distribution分離
- migration失敗 → rollback可能に

---

## Result

**Outcome**
成功 / 部分成功 / 失敗

**Unexpected**
想定外の事象

**Next time**
次回変えること
