## C++ notes for competetive programming

template for competetive programming
```
#include <bits/stdc++.h>
using namespace std;

int main() {
  // solution
}
```

compiling with C++11 standard, optimizing code and showing all warnings about possible errors
```
g++ -std=c++11 -O2 -Wall code.cpp -o bin
```

Input and output is sometimes a bottleneck. Snippet for more efficient code:
```
ios_base::sync_with_stdio(0);
cin.tie(0);
```

using files for input and output. Use the following inside the main file
```
freopen("input.txt", "r", stdin);
freopen("output.txt", "w", stdout);
```


using `\n` is faster because `std::endl` always causes flush operation
```
cout << a <<< "\n";
```

comparing floats
```
if (abs(a-b) < 1e-9) { // a and b are equal
}
```
