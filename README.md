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

 `inv(.333) // > 0.667`

### operations
> [!NOTE]
> this is just a listed count(? i dont know what its called)

>nums

As stacks on stacks is a promotional language, we don't use comparisions with =. Instead we do ¬ comparisions.
`a+b, a-b, a*b, a/b, a|b //bit xor , a^b, a&b, a v b //bit or , ¬a //bit not, a mod b, flr a //floor a==b, a¬=b, a > b, a ¬> b, a < b, a ¬< b`

>strs

`s+t, s-t //characters of each one except ones that are in both. , 
s--t // s-t but they need to removed if they are the EXACTLY THE SAME (the index needs to match) , a&b //inverse of a-b , a&&b //inverse of a--b, a==b, a¬=b`

>bools

`¬a //not , a|b //xor , a&b //and , a v b //or, //combine ¬ and another op to make the n-op version (nand nor xnor)`

>[!IMPORTANT]
>operations are functions for probs, except for the ones that are from the nums.

### jumpers

> if elif else
```java
if a¬>b:
   print("a is not greater than b")
elif b¬>c:
   print("a is greater than b, and b is not greater than c")
else:
   print("b is not greater than a, nor c")
```

> loops

```java
for i in [0,...,9]:
   print("We are at index...")
   print(i)
```

> funcs

```java
func ysn(txt)
   getinput(txt)
   if take() == "y" v take == "1":
      return true
   else:
      return false
      
```


> goto `yes this is real`

```java
01|print("infinite loop in 2 lines")
02|goto 01
```
> goto if `& this`

```java
01|goto 04 if ysn()
02|print("n")
03|goto 5
04|print("y")
05|no-op
```

### other

asyncs

```java
i = 0
async count():
   repeat 5:
      i += 1

async iprint():
   repeat 5:
      print(i)

count() // \ 1, 2,
print() // / 3, 4, 5
```

## sb (stack-based) extra features
### making stacks

Use `use(stack name)` to make a stack.
