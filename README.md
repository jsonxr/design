# design
software design

## Designing for Consistency

### External Consistency

When there is a common convention, try and follow what others have done. If you do this, then it makes it easier for developers to guess what your API is.

Consistent
Unix:  cp from to
Java: Files.copy(from, to)
C#: File.copy(from, to)

Inconsistent
Go (array copy): copy(to, from)

### Internal Consistency
If there is a good reason not to be consistent with what others have done, you need to be consistent with yourself. In the example above, go might have a good reason to put "to" as the first argument. If they have decided that all of their APIs should have the thing they operate on first, at least they would be consisent with themselves.
