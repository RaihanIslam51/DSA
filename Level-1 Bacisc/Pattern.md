# Pattern

### pattern 1:
```cpp
#include <iostream>
using namespace std;

int main() {
    int n = 10;
    for (int i = 0; i < n; i++)
    {
        for (int j = 0; j < n; j++)
        {
            cout << "* ";
        }
        cout << endl;
        
    }
    
    return 0;
}

// Input : 4
// * * * * 
// * * * *
// * * * *
// * * * *
```
### pattern-2
```cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cin >> n;
    for(int i = 0; i < n; i ++){
        for(int j = 0; j < n; j ++){
            cout << i+1 << " ";
        }
        cout << endl;
    }
    return 0;
}

// Input : 5
// 1 1 1 1 1 
// 2 2 2 2 2
// 3 3 3 3 3
// 4 4 4 4 4
// 5 5 5 5 5
```
### pattern -3
```cpp
#include <iostream>
using namespace std;

int main() {
    int n = 3;
    for(int i = 0; i < n; i++){
        for(int j = 0; j < n; j++){
            cout << j + 1 << " ";
        } cout << endl;
    }
    return 0;
}

// Input : 3
// 1 2 3 
// 1 2 3 
// 1 2 3 
```
### pattern 4 :
```cpp

```
