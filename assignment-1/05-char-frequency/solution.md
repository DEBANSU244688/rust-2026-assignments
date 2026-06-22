# Solution notes: Character frequency, sorted

## Approach

_Used HashMap to count the frequencies of the characters and entry() ensures that HashMap is looked for a key once. The or_insert() initializes the count value of corresponding character with 0 and then is incremented by 1 while iterating over the input. Used sort_by() to sort by descending count and ascending character (tie breaker) for already collected Vec<(char, u32)>._

## Edge cases handled

_Empty String, Single character, All same character, All tied counts, Spaces._

## Anything special

_cnt_b.cmp(cnt_a) gives descending order (as original order was |(ch_a, cnt_a), (ch_b, cnt_b)|). .then() evaluates when first comparison returns equal._
