# Recursion

{% code-tabs %}
{% code-tabs-item title="CountDown.aspen" %}
```text
countdown = x ->
    if x > 0
        display concatenate ( String x ) "..."
        countdown ( x - 1 )
    else
        display "Blast Off!"

countdown 5
```
{% endcode-tabs-item %}
{% endcode-tabs %}

```text
 $ Aspen CountDown.aspen
 5...
 4...
 3...
 2...
 1...
 Blast Off!
```

