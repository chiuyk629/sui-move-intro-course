# Unit One Knowledge Quiz

## Q1  

We introduced abilities in this unit, which are critical to how assets are defined in Move. However, some combinations of the four abilities are illegal in Move due to how the abilities operate, which may produce unsafe or conflicting behavior if allowed. 

Mark the following combinations as either legal or illegal:

- Store + Key
- Copy + Drop
- Drop + Store
- Store + Copy
- Key + Copy

For each of the illegal combinations, briefly describe the conflicting behavior that would occur it the combination was allowed. 

*Hint: You can test out these combinations using the compiler. 

## Q2

What's the difference between `sui::transfer::transfer` and `sui::transfer::public_transfer`?