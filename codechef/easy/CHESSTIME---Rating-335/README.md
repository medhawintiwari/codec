# CHESSTIME - Rating 335

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-28T17:16:39.929Z  

```c_cpp
#include <iostream>
using namespace std;

int main() {
    int T;
    cin >> T;
    
    while (T--) {
        int X;
        cin >> X;
        
        if (X <= 70) {
            cout << 0 << endl;
        } else if (X <= 100) {
            cout << 500 << endl;
        } else {
            cout << 2000 << endl;
        }
    }
    
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CHESSTIME)