---
description: Introduces lambdas
---

# Anonymous Functions

What if we have a function that we only need to use once. Defining a whole new function isn't always the best thing to do. 

{% tabs %}
{% tab title="Normal " %}
This is how we'd normally write the code:

```text
square = x -> x * x
-- function : Int -> Int

square 5
-- 25 : Int
```
{% endtab %}

{% tab title="Using lambdas" %}
The same code, but as an anonymous function

```text
( x -> x * x )
-- function : Int -> Int

( x -> x * x ) 5
-- 25 : Int
```
{% endtab %}
{% endtabs %}



