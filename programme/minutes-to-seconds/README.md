---
title: Minutes to Seconds
description: Write a programme to convert minutes to seconds
image: hero.png
tags:
  - python
  - java
  - cpp
  - c
contributors:
  - seraph776
  - MananKarnik
  - siddhantchimankar
  - ClasherKasten
---

## Write a programme to convert minutes to seconds

```txt
Input  : 1
Output : 60
```

---

<CodeBlock>

```python
def minutes_to_second(minutes: int) -> int:
    """converts minutes to seconds"""
    return minutes * 60


if __name__ == '__main__':
    print(minutes_to_second(1))  # 60
    print(minutes_to_second(5))  # 60
    print(minutes_to_second(10))  # 60
```

```java
import java.util.Scanner;

public class MinutesToSeconds {
    // Static method to convert minutes to seconds
    public static int minutesToSeconds(int minutes) {
        return minutes * 60;
    }

    // Driver Code
    public static void main(String[] args) {
        // Accept input from user
        var input = new Scanner(System.in);
        System.out.print("Min: ");
        int minutes = input.nextInt();
        // Convert minutes to seconds
        int seconds = minutesToSeconds(minutes);
        // Print output
        System.out.println("Sec: " + seconds);
    }
}
```

```cpp
#include <iostream>
using namespace std;

int main()
{

    int n;
    cout << "Enter Minutes : ";
    cin >> n;
    cout << "\nSeconds : " << n * 60 << "\n";

    return 0;
}
```

```c
#include <stdio.h>

int main(void)
{
    double minutes;
    printf("Min : ");
    scanf("%lf", &minutes);
    int seconds = minutes * 60;
    printf("Sec : %d\n", seconds);
    return 0;
}
```

</CodeBlock>
