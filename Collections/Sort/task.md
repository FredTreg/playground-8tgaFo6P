## Sort

Implement `Shop.getCustomersSortedByNumberOfOrders()` using
[`sorted`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/kotlin.-iterable/sorted.html) or
[`sortedBy`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/kotlin.-iterable/sorted-by.html).

```kotlin
listOf("bbb", "a", "cc").sorted() == listOf("a", "bbb", "cc")
listOf("bbb", "a", "cc").sortedBy { it.length } == listOf("a", "cc", "bbb")
```

@[Task]({"project": "kotlin-koans", "stubs": ["Collections/Sort/src/Task.kt"], "command": "\"Collections/Sort\" TestSort"})