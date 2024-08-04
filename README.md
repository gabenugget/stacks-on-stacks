# stacks on stacks
stack based language where you make the stacks.
## stacks
you start with 2 stacks: the `main stack`(`m`) and the `control stack`(`c`).
### adding/removing from stack
follow this chart:

|command to use|add to stack |remove from stack|
|--------------|-------------|-----------------|
|      ʌ       |   `push()`  |     `pop()`     |
|      •       |   `ins(i)`  |     `del(i)`    |
|      v       |   `brng()`  |     `take()`    |

No matter what, you ***must*** follow one of these patterns. the `ins(n)` command is used as a example.
* `val.ins(stk, i)`

* `ins(val,stk,i)`

## basic oop actions

yes, this is also object oriented

### types

> num

`1+2 // > 3`

> str

`"hello " + "world!" // > "hello world!"`

> bool

`¬false // > true`

> [!NOTE]
> this is new
> 
> probabitity

 `inv(.333) // 0.667`

### operations
> [!NOTE]
> this is just a listed count(? i dont know what its called)

>nums

`a+b, a-b, a*b, a/b, a|b //bit xor , a^b, a&b, a v b //bit or , ¬a //bit not`

>strs

`s+t, s-t //characters of each one except ones that are in both. , 
s--t // s-t but they need to removed if they are the EXACTLY THE SAME (the index needs to match) , a&b //inverse of a-b , a&&b //inverse of a--b`


### jumpers

> if elif else
