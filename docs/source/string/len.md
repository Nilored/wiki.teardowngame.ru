# string.len

`number string.len( string str )`

| Type   | Argument | Description                       |
|--------|----------|-----------------------------------|
| string | str      | The string to find the length of. |

### Example

Demonstrates the use of this function.

```lua
print( string.len( "hi" ) )
print( string.len( "drakehawke" ) )
print( string.len( "" ) )
print( string.len( "test" ) == #"test" )
```

###### Output:

2

10

0

true