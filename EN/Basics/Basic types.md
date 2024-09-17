1. <span style = "font-size: 20px"><span style = "color: rgb(0, 102, 254)">int</span> - 4 bytes</span>
2. <span style = "font-size: 20px"><span style = "color: rgb(0, 102, 254)">long</span> - 4 bytes</span>
3. <span style = "font-size: 20px"><span style = "color: rgb(0, 102, 254)">long long</span> - 8 bytes</span>
4. <span style = "font-size: 20px"><span style = "color: rgb(254, 107, 0)">char</span> - 1 byte</span>
5. <span style = "font-size: 20px"><span style = "color: rgb(127, 158, 254)">float</span> - 4 bytes</span>
6. <span style = "font-size: 20px"><span style = "color: rgb(127, 158, 254)">double</span> - 8 bytes </span>
7. <span style = "font-size: 20px"><span style = "color: rgb(253, 217, 0)">long double</span> - 16 bytes</span>
8. <span style = "font-size: 20px"><span style = "color: rgb(0, 217, 255)">bool</span> - 1 byte</span>
# Unsigned
<span style = "font-size: 20px"><span style = "color: rgb(254, 107, 0)">Unsigned</span> is a special "prefix" word which means that first bit will not be "reseved" for sign.</span>
\**Note: usually first bit means sign of the number.*
<span style = "font-size: 20px">You can just write <span style = "color: rgb(254, 107, 0)">unsigned</span>. It means <span style = "color: rgb(254, 107, 0)">unsigned</span> <span style = "color: rgb(0, 102, 254)">int</span>. Example:</span>
```cpp
int main(){
	unsigned a = 5; // a is an unsigned int.
}
```
