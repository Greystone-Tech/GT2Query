# GT2Router Query Interface
Simple query tool to pull data from the gt2router instance

## Syntax
```
gt2query -q $field.$value

e.g to query GSM Operator: gt2query -q gsm.operator
```

GT2Query will always force lowercase, so these commands are not case-sensitive

## Available Fields
### Power
* State

### GSM
* CCID
* Operator
* IMEI
* Signal-Quality
* Signal-Strength
