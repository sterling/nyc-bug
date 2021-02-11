# nyc-bug
To reproduce, run `yarn nyc report -t coverage --reporter=text-summary`

Two different results can be returned after multiple runs:

```
Statements   : 96.39% ( 80/83 )
Branches     : 86.96% ( 40/46 )
Functions    : 93.33% ( 14/15 )
Lines        : 96.1% ( 74/77 )
```

```
Statements   : 92.77% ( 77/83 )
Branches     : 81.63% ( 40/49 )
Functions    : 93.33% ( 14/15 )
Lines        : 98.63% ( 72/73 )
```
