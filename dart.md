# Dart

### 1. Default value

> Visit [here](https://dart.dev/guides/language/language-tour#default-value) to get more

* Uninitialized variables that have a **nullable type** have an initial value of **null**. => Every variable that is uninitialized has a null value.
* Code example:

```dart
int? age;
assert(age === null)
// In the productions will ignore an assert, 
// it is only called in development.
// assert(condition) will throw exceptions when the condition is false.
```



### 2. Late variables

> Visit [here](https://dart.dev/guides/language/language-tour#late-variables) to get more

* Important:

```dart
late String temperature = readThermometer(); // Lazily initialized.
// functions readThermometer only called when temperature is used
```

### 3. Final and Const

> Visit [here](https://dart.dev/guides/language/language-tour#final-and-const) to get more

* If you never intend to change a value use **final** or **const**, instead of var or addition type.
* Code example

```dart
final name = "Long";
final String name = "Long"
// or
const age = 18;
const int age = 18;

```

> To know what different between const and final, please visit [here](https://stackoverflow.com/questions/50431055/what-is-the-difference-between-the-const-and-final-keywords-in-dart)

### 4. Built-in types

> Visit [here](https://dart.dev/guides/language/language-tour#built-in-types)



### 1. Type systems

* Dart uses a combination of static type checking and [runtime checks](https://dart.dev/guides/language/type-system#runtime-checks) to ensure that a variable’s value always matches the variable’s static type.

### 1. Functions

#### 1. Anonymous Functions

* Anonymous functions are like named functions but they don't have a **name.**&#x20;
* Syntax:

```dart
(parameters list) {
statement(s)
}
```

* Code examples:&#x20;

```dart
void main(){
 const subjects = ["Math", "History", "Chemistry"]
 subjects.forEach((subject){
  print("Subject: $subject");
 })
}
```

#### 2. Different types of functions

> There are four types of functions in dart:

* No arguments and no return type

```dart
void myName (){
 print("Tran Cao Phuoc Long!!");
}
```

* With arguments and no return type

```dart
void plus(int a, int b){
print("Result a + b: $(a+b)")
}
```

* No arguments and return type

```dart
String getName(){
    String myName = "Tran Cao Phuoc Long";
    return myName;
}
```

* With arguments and with return type

```dart
import "dart:core"
int calculate(int year){
     final now = DateTime.now();
     print("Your age is: $(now.year - year)")
}
```





