<span style = "font-size:20px">When scope ends(at } symbol) all variables with basic type, which was declared in this scope are being deleted. All custom types call the destructor. Scope is setting with {}. You can set it in any moment.</span>
```cpp
int func(){
	{}; // <- scope
}
```
<span style = "font-size:20px">You can apply to global variable in any scope.</span>
```cpp
#include <iostream>
using namespace std;

int x = 5; // global variable 

int main(){

    int x = 7;

    {

        int x = ::x;

        cout << x << endl;

    }

    cout << x << endl;

    cout << ::x << endl;

}
```

```cpp
Output:
5
7
5
```
