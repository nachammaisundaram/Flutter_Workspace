---

# Conditional Statements

## 5. if-else with a Boolean Variable

A `bool` can hold only two values: `true` or `false`. The `if` block runs when the value is `true`, otherwise the `else` block runs.

```dart
void main() {
  bool rain = true; // change to false to see the other output

  if (rain) {
    print("Take an umbrella");
  } else {
    print("Enjoy the sunlight!");
  }
}
```

**Output:**

```text
rain = true   ->  Take an umbrella
rain = false  ->  Enjoy the sunlight!
```

## 6. Another if-else Example

```dart
void main() {
  bool holiday = true; // change to false to see the other output

  if (holiday) {
    print("Go out with friends");
  } else {
    print("Get ready for college");
  }
}
```

**Output:**

```text
holiday = true   ->  Go out with friends
holiday = false  ->  Get ready for college
```

---

# Comparison Operators

| Operator | Meaning | Example | Result |
|---|---|---|---|
| `>` | Greater than | `10 > 5` | `true` |
| `<` | Less than | `10 < 5` | `false` |
| `>=` | Greater than or equal to | `35 >= 35` | `true` |
| `<=` | Less than or equal to | `20 <= 10` | `false` |
| `==` | Equal to | `10 == 10` | `true` |
| `!=` | Not equal to | `10 != 20` | `true` |

A comparison always gives a `bool` result (`true` or `false`).

## 7. Printing a Comparison Result

```dart
void main() {
  print(5 > 10);
}
```

**Output:**

```text
5 > 10   ->  false
11 > 10  ->  true
```

## 8. Comparing Two Variables

```dart
void main() {
  int a = 10;
  int b = 20;

  if (a > b) {
    print("$a is greater than $b");
  } else {
    print("$b is greater than $a");
  }
}
```

**Output:**

```text
20 is greater than 10
```

## 9. Guess the Output

```dart
void main() {
  if (10 < 5) {
    print("10 is greater than 5");
  }
}
```

**Question:** Will the output be `10 is greater than 5`?

**Answer:** No. `10 < 5` is `false`, so the `if` block does not run. There is no `else` block, so the program prints **nothing**.

## 10. Pass or Fail Check

```dart
void main() {
  int score = 79; // try 20 and 35

  if (score >= 35) {
    print("PASS");
  } else {
    print("FAIL");
  }
}
```

**Output:**

```text
score = 79  ->  PASS
score = 20  ->  FAIL  (20 >= 35 is false)
score = 35  ->  PASS  (35 >= 35 is true)
```

## 11. Equality Check

```dart
void main() {
  int a = 10;
  int b = 20; // change to 10 to see the other output

  if (a == b) {
    print("equal");
  } else {
    print("not equal");
  }
}
```

**Output:**

```text
b = 20  ->  not equal
b = 10  ->  equal
```

**Note:** `=` assigns a value, `==` compares two values.