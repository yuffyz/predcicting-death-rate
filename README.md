# predcicting-death-rate
gradient descent


```bash
grep 'MANHATTAN' violations.csv > man.csv
head -1 violations.csv > header.txt
cat header.txt man.csv > manViolation.csv
```

```python
manViolation['InspectionDate'] = pd.to_datetime(manViolation['InspectionDate'])
df = manViolation[(manViolation['InspectionDate']> datetime.date(2018,9,30)) & (manViolation['InspectionDate']<datetime.date(2019,1,1))]
```
