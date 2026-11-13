# HOTCOLD - Rating 460

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-13T09:44:13.434Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int x;
    double y;
    if (!(cin >> x >> y)) return 0;
    if (x % 5 == 0 && y >= x + 0.50) {
        cout << fixed << setprecision(2) << y - x - 0.50 << endl;
    } else {
        cout << fixed << setprecision(2) << y << endl;
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/HOTCOLD)