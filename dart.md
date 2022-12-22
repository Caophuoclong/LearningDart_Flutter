# Dart

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





