# Solution notes: Censor vowels in place

## Approach

_Used .chars().map(|c| ...).collect() to build a copy where the closure replaces every ASCII vowel with '*' and others unchanged. Then replaced the contents of s in place using .clear() and then pushed the censored using .push_str()._

## Edge cases handled

_Empty String, No vowels, All vowels, Mixed case vowels, Non-ASCII characters, Digits & Punctuation._

## Anything special

_Tricks, alternatives you considered, performance notes, etc._
