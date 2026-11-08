# MINCOINSREQ - Rating 383

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-11-08T17:15:29.759Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    int t;
    cin >> t;
    while (t--) {
        int n, m, x;
        cin >> n >> m >> x;
        int ans = 2 * (n + m) * x;
        cout << ans << endl;
    }
    return 0;
}
```

---

[View on CodeChef](https://www.codechef.com/problems/MINCOINSREQ)