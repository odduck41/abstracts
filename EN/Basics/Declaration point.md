<span style = "font-size:20px">A variable is considered declared after setting the variable type* and name.</span>

```cpp
	int x/* declaration point is here */ = 5;
```

\*Type of variable can be "composite"(e.x. int[5]).
```cpp
int main(){
	int x = 2;
	{
		int x[x]/* declaration point is here */= {1, 2}; // In this scope x is an array of two numbers
	}
}
```
