## Lazy property

Add a custom getter to make the 'lazy' val really lazy.
It should be initialized by the invocation of 'initializer()' at the moment of the first access.

You can add as many additional properties as you need.

Do not use delegated properties!

@[Task]({"project": "kotlin-koans-3-1", "stubs": ["src/Task.kt"], "command": "TetLazyProperty"})