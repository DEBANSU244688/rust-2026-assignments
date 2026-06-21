# Solution notes: Reverse the word order

## Approach

_Used split_whitespace() to get an iterator of &str slices with striped leading/trailing whitespaces. Called rev() to reverse the iterator and collect it as Vec<&str> and joined with single space using .join(" ")._

## Edge cases handled

_Empty string, Whitespace only string, Multiple consecutive spaces, Leading/Trailing whitespaces, Tabs & newlines, Single Word._

## Anything special

_Tricks, alternatives you considered, performance notes, etc._
