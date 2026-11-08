# CWIREFRAME - Rating 382

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-08T17:15:15.729Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int t;
    cin >> t;
    while (t--) {
        int x, y;
        cin >> x >> y;
        int d = 3 * x;
        int tr = 2 * y;
        if (d < tr) {
            cout << d << endl;
        } else {
            cout << tr << endl;
        }
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/CWIREFRAME)