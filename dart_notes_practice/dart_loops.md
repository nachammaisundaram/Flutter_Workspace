# Functions

A **function** is a block of code with a name. We write it once and call it whenever we need it, so we don't repeat the same code.

## 1. Simple Functions

`void` means the function does its work but does not return any value.

```dart
void apple() {
  print("This is an Apple phone");
}

void samsung() {
  print("This is a Samsung phone");
}

void redmi() {
  print("This is a Redmi phone");
}

void main() {
  apple();
  samsung();
  redmi();
}
```

**Output:**

```text
This is an Apple phone
This is a Samsung phone
This is a Redmi phone
```

**Note:** A function runs only when it is **called**. Defining it alone does nothing.

## 2. Parameters and Arguments

- **Parameter:** the variable written in the function definition (`int price`).
- **Argument:** the actual value passed when calling the function (`100000`).

```dart
void apple(int price) {
  print("Price of Apple phone: $price");
}

void showroom(String name) {
  print("Showroom name: $name");
}

void main() {
  apple(100000);
  showroom("Chennai Mobiles");
}
```

**Output:**

```text
Price of Apple phone: 100000
Showroom name: Chennai Mobiles
```

## 3. Passing Two Values

```dart
void add(int a, int b) {
  int c = a + b;
  print(c);
}

void main() {
  add(10, 10);
}
```

**Output:**

```text
20
```

---

# For Loop

A **loop** repeats a block of code multiple times.

```text
for (start; condition; update)
```

| Part | Meaning | Example |
|---|---|---|
| Start | Where the counter begins | `int count = 1` |
| Condition | Loop continues while this is `true` | `count <= 3` |
| Update | Changes the counter after each round | `count = count + 1` |

## 4. Simple For Loop

```dart
void main() {
  for (int count = 1; count <= 3; count = count + 1) {
    print("Nach");
  }
}
```

**Output:**

```text
Nach
Nach
Nach
```

## 5. Print Numbers from 1 to 10

```dart
void main() {
  for (int count = 1; count <= 10; count = count + 1) {
    print(count);
  }
}
```

**Output:**

```text
1
2
3
4
5
6
7
8
9
10
```