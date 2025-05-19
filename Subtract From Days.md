
###  Power Automate - Deduct days from timestamp number.

```

addDays(
    startOfMonth(
        addDays(
            startOfMonth( utcNow() ),
        31)
    ),
    -1
)
```
