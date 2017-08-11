## Fold

Implement `Shop.getSetOfProductsOrderedByEveryCustomer()` using
[`fold`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/kotlin.-iterable/fold.html).

```kotlin
listOf(1, 2, 3, 4).fold(1, {
    partProduct, element ->
    element * partProduct
}) == 24
```


@[Task]({"project": "kotlin-koans-2-9", "stubs": ["src/Task.kt"], "command": "TestFold"})