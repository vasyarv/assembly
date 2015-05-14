
```c
int sum(int a,int b);

int main() {
        int result = sum(1,2);
        return result*2;

}
```

```c
int sum(int a, int b) {
        return a + b;
}
```

gcc -o program main.c sum.c
