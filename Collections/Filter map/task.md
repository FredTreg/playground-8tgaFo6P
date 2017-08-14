## Filter; map

Implement extension functions `Shop.getCitiesCustomersAreFrom()` and `Shop.getCustomersFrom()` using functions
[`map`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/kotlin.-iterable/map.html) and
[`filter`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/kotlin.-iterable/filter.html).

```kotlin
val numbers = listOf(1, -1, 2)
numbers.filter { it > 0 } == listOf(1, 2)
numbers.map { it * it } == listOf(1, 1, 4)
```

@[Task]({"project": "kotlin-koans", "stubs": ["Collections/Filter map/src/Task.kt"], "command": "\"Collections/Filter map\" TestFilterMap"})