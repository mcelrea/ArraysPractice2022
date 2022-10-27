# Array Notes

### Accessing the last element of an array

This is how you ***always*** access the last element of any array

```java
arrayName[arrayName.length-1]
```

### Array declaration

There are 3 ways to declare an array. The most common way is to declare and initialize in the same line. For Example:
All the below examples, create 10 element arrays filled with default values.

```java
int[] nums = new int[10];
double[] vals = new double[10];
boolean[] flags = new boolean[10];
String[] names = new String[10];
```

Secon way, less common, is to declare an array, and later intialize it. We
often do this if we **don't know** the size of the array when we declare it.

```java
int nums[];
//some code goes here
//later I initialze the array
nums = new int[10];
```

Third way is to use an array initializer. We can only do this
if we know the values we want int he array.

```java
int nums[] = {3,5,6,7,8,1};
double vals[] = {3.5,8.9,1.2};
boolean flags[] = {true, false, false};
String names[] = {"McElrea", "Jason", "Neil"};
```

