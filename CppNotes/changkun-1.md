# Lesson 1

## Initialization List:

```cpp
class Test {
public:
    int a;
    int b;
    int c;

    Test(int a, int b, int c) : a(a), b(b), c(c) {
        this -> a = a;
        this -> b = b;
        this -> c = c;
    }
};

int main() {
    Test test {1, 2, 3};

    cout << test.a << " " << test.b << " " << test.c << endl;
}
```

You can initialize the values by listing them with {} syntax. 

## Constants as Template parameters:

```cpp
template <int size>
class Buffer {
public:
    int data[size];
};
```

Here, we can use size to declare an array, since size is a constant template type! It's amazing! :D:D:D:D:D
