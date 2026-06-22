# Solution notes: Inventory

## Approach

_Restock: Used into_iter() to consume the vector and entry it's element into a hashmap to overcome overlaps, also chained the more vector similarly and returned the vector collected from hashmap. Summary: Used the borrowed slices and calculated their len and sum of quantities through len() & .iter().map(...).sum() and returned the formated result using format!._

## Edge cases handled

_Both Inputs Empty, One Input Empty, Duplicate Names Across Both & Single Input, Summary on Empty Inventory._

## Anything special

_Tricks, alternatives you considered, performance notes, etc._
