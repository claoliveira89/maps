# LECTURES

## 49. What's a Map?
- It's a collection of key/value pairs;
- Both keys and values are staticly typed: all the keys have to be the same type such as all the values. But keys and values does not have to be the same type.

## 50. Manipulating Maps
- We should always use the square braces syntax with maps:

        $   colors["white"] = "#ffffff"

## 52. Differences Between Maps and Structs
> MAP 
>
>> All keys must be the same type
>
>> All values must be the same type
>
>> Keys are indexed - we can iterate over them
> 
>> Use to represent a collection of related properties
>
>> Don't need to know all the keys at compile time
> 
>> Reference Type!
> -------------------------------------------

> STRUCT
>
>> Values can be of different type
>
>> Keys don't support indexing
>
>> You need to know all the different fields at the compile time
>
>> Use to represent a "thing" with a lot of different properties
>
>> Value Type!
> --------------------------------------------
