# C# Programming
This is the summarize of Youtue "Goldmetal" Channel's C# Programming Lecture

[https://www.youtube.com/watch?v=j6XLEqgq-dE](https://www.youtube.com/watch?v=j6XLEqgq-dE)

## Display on Debug
```C#
Debug.Log("HelloWorld");
```

## Type

```C#
int level = 5;
float strength = 15.5f;
string playerName = "NANA";
bool isFullLevel = false;
```

- int: integer
- float: float( put `f` on the last of value )
- string: string
- bool: boolean

## Comment
`//line Comment`

## Group Variable: Array

### Declaration with Initialization

```C#
string[] monsters = {"monster1", "monster2", "monster3"};
Debug.Log(monsters[0]);
```

### Declaration and then Initialization

```C#
int[] monsterLevel = new int[3];
monsterLevel[0] = 1;
monsterLevel[1] = 1;
monsterLevel[2] = 1;
```

### Generic

```C#
List<string> items = new List<string>();
items.Add("Potion");
itmes.RemoveAt(0);
```

## Operator

### Numeric
```C#
int exp = 1500;
exp = exp - 10; 
level = exp / 300; 
strength = level * 3.1f;

int nextExp = 300 - (exp % 300);
```

### String
```C#
string title = "Legend";
Debug.Log(title + " " + playerName);
```

### Bool
```C#
int fullLevel = 99;
isFullLevel = level == fullLevel; //false
```
- &&: AND
- ||: OR
- Tenary:
```C#
bool condition = isBadCondition ? "Good" : "Bad";
```

## Class
```C#
public class NewClass(){

}
```
- 전역 개념이 없다. 모든 것은 클래스의 멤버 변수 혹은 함수이다.
