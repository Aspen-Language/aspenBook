# Function Composition

```text
f : Int -> Int
g : Int -> Int

f = x -> 2 * x
g = x -> x + 1

h = x : f ( g x )
h = f <- g

x = ( x : Int )
```

