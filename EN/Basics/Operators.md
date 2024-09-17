```cpp
	+    <<    &&
	-    >>    ||
	*     &    !
	/     |
	%     ^
	      ~
```

<span style = "font-size:20px"><span style = "color:red">&&</span> and <span style = "color:red">||</span> don't have to calculate the right part if everything is clear on the left.</span>
# Assignment operator
<span style = "font-size:20px">Expression x = y = 3 assign 3 to x and y. Assignment expressions is executing from right to the left. It means that firstly y become 3, then x become 3. Assignment operator returns reference to right part.<p></p></span>
```cpp
(x = 3) = 5;
```
<span style = "font-size:20px"><p></p>(x = 3) returns x. So after this expression x become 5</span>

```cpp
if (x = 3){
	...
}
```
<span style = "font-size:20px"><p></p>This is correct because x = 3 returns integer, which we can convert to bool</span>
# Addition operators
```cpp
	+=    <<=
	-=    >>=
	*=    &=
	/=    |=
	%=    ^=
```
<span style = "font-size:20px">Returns reference to right part like =.
x += y is more effecive than x = x+y, because + (like other operators) makes a copy.</span>
# Сomparison operators
```cpp
	==    !=
	 <    >
	<=    >=
```
<span style = "font-size:20px"><p></p>Returns bool</span>
# Ternary operator
<span style = "font-size:20px">The only one operator, which requires 3 operands. Syntax:</span>
```cpp
	x ? y : z;
```
<span style = "font-size:20px">If x is true, y is returned, else z is returned.</span>
# Increment 'n decrement
<span style = "font-size:20px">Syntax:</span>
```cpp
	++x;
	x++;
	--x;
	x--;
```
<span style = "font-size:20px">++x adds 1 to x and returns reference to x. x++ copies x, adds 1 to  x and returns copy of x.</span>
```cpp
	++x = 5;
	x++ = 5; //Error
```
# Sizeof() operator
<span style = "font-size:20px">Returns count of bytes, which this type would use.</span>
```cpp
	int x = 5;
	cout << sizeof(x) << endl;//4
	cout << sizeof(int) << endl;//4
```
# Comma operator
<span style = "font-size:20px">Counts firstly left, then right parts, then returns right part.</span>
```cpp
	int x = (5, 3);//x = 3
```
<span style = "font-size:20px">Comma has the lowest priority.</span>
# Important
```cpp
	func(arg1, arg2); // comma is not operator here
	int x = 5; // = is not assignment operator here, it is declaration
```
