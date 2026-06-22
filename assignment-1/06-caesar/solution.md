# Solution notes: Caesar cipher

## Approach

_Iterated over input.chars() and mapped for each ASCII alphabet by determining it's base and computing it's 0 based position within 26 letters(0-25). Then added the shift and wrapped with rem_euclid() to reconstruct the character._

## Edge cases handled

_Non letters, Negative Shift, Shift larger Than 26, Shift Of 0 & 26, Uppercase Letters, Large Negative Shift (<-26)._

## Anything special

_Used rem_euclid() as it returns non-negative remainders [0, n) instead of negative as like % in Rust. Coverted ALPHABET.len() as i32 to satisfy the type._
