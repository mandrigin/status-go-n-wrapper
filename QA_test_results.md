# Energy consumption test results

## Add new
- [Click to add](https://github.com/mandrigin/status-go-n-wrapper/compare/master...report/example?quick_pull=1&template=test_result_pr_template.md&title=Energy%20consumption%20test%20result%20for%20build:%20{build%20name},%20os:%20{Android,%20iOS}) new result of a [manual energy consumption test](./QA.md)

## Manual test results

|Date|Build|Platform|Test session|Device|Conditions|Battery (total)*|Battery (CPU)*|Total data transferred*|Logs|PR|
|---|---|---|---|---|---|--|--|--|--|--|
|2018-03-22|581d4f (2018-03-22 nightly)|Android|Release testing (30 min)|Samsung Galaxy S8|wifi only, 50% screen brightness|1.32%|2.21%|79.95MB|bugreport-2018-03-22-14-30-42.zip|#3|
|2018-03-17|9533d1 (2018-03-17 nightly)|Android|Release testing (30 min)|Samsung Galaxy S8|wifi only, 50% screen brightness|0.97%|1.53%|43.42MB|bugreport-2018-03-17-11-32-14.zip||

----
**Battery (total)** - Device estimated power use

**Battery (CPU)** - Device estimated power use due to CPU usage

**Total data transferred** - Wifi data + Mobile data that was transferred

**PR** - Pull request ID with test report
