# nrb-wrangle
bonus challenge

## Assigned play -Tragedy(Hamlet)- number 3
-[play link](http://shakespeare.mit.edu/hamlet/full.html)

## Speakers 
1. HAMLET
2. HORATIO

## Commands used are 
``` 
curl "http://shakespeare.mit.edu/hamlet/full.html" -O "input.txt"
``` 
```
$ curl "http://shakespeare.mit.edu/hamlet/full.html" | sed 's/<\/*[^>]*>//g' >input.txt
```
```
grep 'HAMLET' input.txt -c
```
``` 
grep 'HORATIO' input.txt -c 
```
``` 
grep 'HAMLET' input.txt' -c > 'Hamlet.txt'
```
```
grep 'HORATIO' input.txt' -c > 'Horatio.txt'
```
## Does Speaker 1 speaks more than Speaker 2 ??
- In this case, Speaker 1 Hamlet speaks more i.e 386 times than Speaker 2 'Horatio'(127 times)



