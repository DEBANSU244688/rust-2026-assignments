# Solution notes: Longest word slice

## Approach

_Used split_whitespace() to get an iterator of &str slices. Used .reduce() with a closure to keep the longer word between two words. reduce() returns None when iterator is empty(either only whitespaces or empty inputs)._

## Edge cases handled

_Empty String, Whitespace only String, Single word, Tie(First one returned), Leading/Trailing Whitespace._

## Anything special

_Tricks, alternatives you considered, performance notes, etc._
