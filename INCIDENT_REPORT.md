# Incident Report: Payment Commission Bug

## Bug Discovery
- Found using: [команда bisect которую использовали]
- Problematic commit: [SHA коммита]
- Author: [из git blame]

## Root Cause
The bug was introduced in the "Optimize commission calculation" commit where:
1. Commission calculation was changed to return rate instead of amount
2. [Опишите что именно было неправильно]

## Fix Applied
- Reverted commit: [SHA]
- Fix commit: [SHA]
- Verification: [как проверили что исправлено]

## Stash Usage
- Stashed work: [описание что было в stash]
- Stash command used: [команда]
- Recovery successful: Yes/No

## Reflog Recovery
- Lost commit: [что потеряли]
- Recovery command: [команда из reflog]
- Restored SHA: [SHA]

## Lessons Learned
[По сути никаких проблем не было при решении задач. При слияние и написание веток ошибок не было
Так что, все прошло гладко. Так и должно быть? Type Shit]
