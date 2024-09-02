# Go: Data Types

### Built-in Types
- Booleans
- Integers:
    + Default is base 10
    + Binary: 0b
    + Octal: 
        + 0o
        + It often used to represent POSIX permission flag values like 0o777,...
    + Hexa: 0x
    + Rune: represent characters and are surrounded by single quotes. ('a', 'b', ...)
    + Types: int8, int16, int32(__rune__), int64, uint8 (_byte_), uint16, uint32, uint64
    + Special types: 
        + __int__ (32 bit or 64 bit depend on platform)
        + __uint__
        + __rune__ (alias for int32)
        + __uintptr__
- Floats
- Strings
- Complex

#### 1. Integers 
- The result of an __integer / integer__ is an __integer__.
- Divide an integer by 0 cause a panic.
- Integer division truncate toward zero.

#### 2. Floats
- Float store the nearest appoxiamtion.
> __Do not use floats to represent money or any other value thats mmust have an exact decimal representation.__

```text
- Positive float / 0 = +Inf
- Negative float / 0 = -Inf
- 0 / 0 = NaN
```
> Do not use == and != to compare floats. Instead, define a maximum allowed variance and see if the difference between two floats is less than that.

#### 3. Strings
- The zero value is the empty string.
- That can use ==, !=, >, >=, <, <= to compare two strings, + to concat strings.
- Strings in Go are immutable, we can not change the value of the string that is assigned to it.

### Type conversion
- Go doesn't allow automatic conversion between types.
- We cannot treat another Go type as a boolean, only using comparison operators. 
