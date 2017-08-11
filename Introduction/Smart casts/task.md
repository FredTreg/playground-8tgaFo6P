## Smart casts

Rewrite the following Java code using [smart casts](http://kotlinlang.org/docs/reference/typecasts.html#smart-casts)
and [when](http://kotlinlang.org/docs/reference/control-flow.html#when-expression) expression:

```java
public int eval(Expr expr) {
    if (expr instanceof Num) {
        return ((Num) expr).getValue();
    }
    if (expr instanceof Sum) {
        Sum sum = (Sum) expr;
        return eval(sum.getLeft()) + eval(sum.getRight());
    }
    throw new IllegalArgumentException("Unknown expression");
}
```

@[Task]({"project": "kotlin-koans-0-8", "stubs": ["src/Task.kt"], "command": "TestSmartCasts"})