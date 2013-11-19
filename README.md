utils
=====

Small shared utilities set

# Usage

The `org.nnsoft.trudeau.utils.Assertions` makes more compact methods arguments validation, such as:

 * `void checkArgument( boolean expression, String errorMessageTemplate, Object... errorMessageArgs )`
 
 * `void checkState( boolean expression, String errorMessageTemplate, Object... errorMessageArgs )`
 
 * `<T> T checkNotNull( T reference, String errorMessageTemplate, Object... errorMessageArgs )`

The `org.nnsoft.trudeau.utils.Objects` simplifies the construction of `boolean equals(Object o)` and `int hashCode()` methods:

 * `<O> boolean eq( O o1, O o2 )`
 
 * `int hash( int initialNonZeroOddNumber, int multiplierNonZeroOddNumber, Object...objs )`

## Note

Yes, we know, there are dozens of libraries across the web that do exactly the same thing, but we just need a subset of 2 classes… does it make sense to import a dependency for few methods? :)