# Solution notes: Group anagrams

## Approach

_Used a HashMap to map the sorted character representation of each word to it's group index and iterated through each word in input list to convert the word to lowercase and sort its characters to create the key. Then used the sorted key to create/find the group in HashMap and appended the original word to the corresponding group in the result vector._

## Edge cases handled

_Empty Input, No Anagrams, All Words Are Anagrams, Single Word, Case-Insensitive Matching, Words Of Different Lengths, Insertion Order Within A Group._

## Anything special

_Used or_insert_with() so that new group creation only happens when key is genuinely absent, instead of or_insert(groups.len()) which would evaluate groups.len() before knowing whether the key exisits, which would give wrong index when the key is already present._
