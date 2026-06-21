# Solution notes: Run-length encode

## Approach

_Iterated over input.chars() and matched the last mutable reference (char, u32) from result.last_mut(). If last pair's character matched with current one the incremented the count in place, else pushed a new (ch, 1) pair._

## Edge cases handled

_Empty String, Single Character, All Same Character, All different character, Whitespace characters._

## Anything special

_Used last_mut() to update the count value in place._
