Given an arbitrary ransom note string and another string containing letters from all the magazines, write a function that will return true if the ransom note can be constructed from the magazines ; otherwise, it will return false.

#### Assumption
1. each letter in the magazine string can only be used once in your ransom note.
1. both strings contain only lowercase letters.

#### Example
```
canConstruct("a", "b") -> false
canConstruct("aa", "ab") -> false
canConstruct("aa", "aab") -> true
```
