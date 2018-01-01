# Java Data Structures Cheatsheet

## Array
```
int a[]=new int[5]; 
```

### Two-Dimensional Array
```
int[][] arr=new int[2][3]; //2 rows and 3 columns
```

## ArrayList
```
ArrayList<Integer> myList = new ArrayList<>();
```

### Insert
```
myList.add(0); //Inserts '0' at the end
myList.add(1,0); //Inserts '0' at index '1'
```


### Get
```
myList.get(0); //Gets first element
```

### Remove
```
myList.remove(0); //Removes object at index '0'
```

## Linked List

## HashMap (HashTable)

## Stack
```
Stack myStack = new Stack();
```

### Push
```
myStack.push("Hello"); // Pushes an item onto the top of this stack.
myStack.push(1);
```

### Pop
```
myStack.pop (); // Removes the object at the top of this stack and returns that object as the value of this function.
```

### Peek
```
myStack.peek(); // Looks at the object at the top of this stack without removing it from the stack.
```

## Queue
```
Queue<String> myQueue = new LinkedList<String>();
Queue<Integer> myNumbers = new LinkedList<Integer>();
```

### Add
```
myQueue.add("Hello");
myQueue.add("World");
myNumbers.add(1);
myNumbers.add(2);
```

## Heap
