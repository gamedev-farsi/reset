+++
title = 'recursion در زبان سی'
date = 2023-01-15T09:00:00-07:00
draft = true
tags = ['برنامه نویسی', 'صفحه آزمایشی', 'صفحه']
summary = 'زبان برنامه نویسی C'
+++

# C

### Recursive example

```c
int sum(int k);

int main() {
  int result = sum(10);
  printf("%d", result);

  return 0;
}

int sum(int k) {
  if (k > 0) {
    return k + sum(k -1);
  } else {
    return 0;
  }
}
```



### Mathematical functions

```c
#include <math.h>

void main(void) {
  printf("%f", sqrt(16)); // square root
  printf("%f", ceil(1.4)); // round up (round)
  printf("%f", floor(1.4)); // round up (round)
  printf("%f", pow(4, 3)); // x(4) to the power of y(3)
}
```