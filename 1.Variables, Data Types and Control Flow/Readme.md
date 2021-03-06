## 1. Data Types overview:
Numeric
- Int32 (signed integers): 10, 299, -100
- Long (Int64, long integers): 5425425532
- Double (allow decimals, 15-16 digits): 15.24561376143

Boolean
- True or False; 0 or 1

Date and Time
- DateTime (store specific date time): mm/dd/yyy hh:mm:ss
- TimeSpan (store duration of time): dd:hh:mm:ss

String

Collection
- Array: store multiple values with the same data type. The size is defined at creation
- List: store multiple values with the same data type. The size is dynamic
- Dictionary: key and value pairs, they can be separate data types

Generic Variables:
When developing an automation process, you are not sure what type of data will be retrieved
- Can store any kind of data. The data type will be based on the first retrieved data 

## 2. Control Flow overview:
Sequences
- Easy to read, edit
- Recommended for Linear workflows

Flowcharts
- More complex
- Recommended for complex scenarios, branches

Statements:
if/else decision
loops
switch

### A. Loops
- Do While
1. Execute the actions
2. Check conditions -> If it's true then continue to do it

- While
1. Check conditions -> If it's true then do the following actions
2. Execute the actions

- For Each
Iterating all items in a list/ array
