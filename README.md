## Work in progress

- 100daysofcode
- codewars
- DATALGO in DBTC
- ProjectEuler

### ProjectEuler

```
# Problem 2: Even fibonacci Numbers
def fibonacci(n):
    a, b = 1, 0
    while a <= n:
        yield a
        a, b = a+b, a

def fiboEvenSum(n):
    return sum(i for i in fibonacci(n) if not i%2 )
```

```
# Problem 1: Multiples of 3 and 5
def multiplesOf3and5(number):
    return sum(i for i in range(number) if i%3 == 0 or i%5 ==0)
```

### Website

[www.rslruiz.com](http://www.rslruiz.com)

### Contact

rslruiz@icloud.com, rslruiz@one-bosco.org
