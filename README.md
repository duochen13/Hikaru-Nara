
### Hash
- [Two Sum 1](./Hash/TwoSum/Solution.java)

### Stack
- [ValidParentheses 20](./Stack/ValidParentheses/Solution.java)
- [TrappingRainWater 42](./Stack/TrappingRainWater/Solution.java)
- [DailyTemperature 739](./Stack/DailyTemperatures/Solution.java)

### Notes
```
character space (1-26) is constant space
String s -> s.toCharArray() || s.charAt(index)
memo.put(c, memo.getOrDefault(c, 0) + 1);
memo.put('c') instead of memo.put("(");
Map<Character, Character> memo = new HashMap<Character, Character>();
java.util.EmptyStackException
use stack to store index or tuple maybe better when input list is fixed
```

### TBR
```
LinkedList vs ArrayList vs Array
```