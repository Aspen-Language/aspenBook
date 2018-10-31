# Recursion

## Examples

```text
sort : List -> List
sort : x ->
    if ( length x ) == 1 |>
        x
    |>
        y = min x
        append y ( sort ( remove y x ) )
```

{% code-tabs %}
{% code-tabs-item title="CountDown.aspen" %}
```text
countdown = x ->
    if x > 0 |>
        display concatenate ( String x ) "..."
        countdown ( x - 1 )
    |>
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

