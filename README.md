# Notes
## Start the Cargo Project
Run the commands:
```
>> cargo new src/placement-center --lib
>> cargo new src/cmd --bin
>> cargo new src/protocol --lib
>> cargo new src/clients --lib
>> cargo new src/common/base --lib
```

## Commands Line
### Difference between `=` and `:=`
- `=` (deferred assignment): The right-hand side is not evaluated until the variable is actually used. This means that the value of the variable can change if the right-hand side expression changes.
- `:=` (immediate assignment): The right-hand side is evaluated immediately when the line is read. This means that the value of the variable is fixed at the time of assignment.
