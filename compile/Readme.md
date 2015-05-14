
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

```bach
gcc -o program main.c sum.c
./program; echo $?
```

```bash
gcc -c main.c
gcc -c sum.c
gcc -o program main.o sum.o
```
