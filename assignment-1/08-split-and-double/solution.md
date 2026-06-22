# Solution notes: Split and double

## Approach

_Used split_at_mut() to obtain two disjoint &mut [i32] slices and iterated over each slice with iter_mut() to double evry element in place. At last returned the slices as tuple pair._

## Edge cases handled

_Mid equals to 0, Mid equals to length of vector, Mid greater than length of vector, Empty vector, Negative Values, Zeros._

## Anything special

_Used split_at_mut() to overcome second mutable borrow (compile error)._
