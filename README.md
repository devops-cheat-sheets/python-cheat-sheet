# Python Cheat Sheet


 
### Data Types

| Command | Description |
| ------ | ------ |
| int("123") | Convert a string or number to an integer |
| float("123") | Convert a string or number to a float |
| str(123) | Convert a number or boolean to a string |
| bool("abc") | Convert a value to a boolean |

### Lists

| Command | Description |
| ------ | ------ |
| list.append(item) | Append an item to the end of the list |
| list.insert(index, item) | Insert an item at a given position |
| list.remove(item) | Remove the first occurrence of a value |
| list.pop([index]) | Remove and return the item at index (default last) |
| list.index(item) | Return zero-based index in the list of the first item whose value is equal to x |
| list.count(item) | Return the number of times x appears in the list |
| list.sort(key=None, reverse=False) | Sort the items in the list in ascending order |
| list.reverse() | Reverse the elements of the list in place |
| len(list) | Return the number of elements in the list |

### Strings

| Command | Description |
| ------ | ------ |
| str.capitalize() | Capitalize the first character of the string |
| str.upper() | Convert all characters of the string to uppercase |
| str.lower() | Convert all characters of the string to lowercase |
| str.swapcase() | Swap case of each character |
| str.title() | Titlecase the string |
| str.find(sub[, start[, end]]) | Return the lowest index in the string where substring is found |
| str.replace(old, new[, count]) | Replace occurrences of a substring within the string |
| str.split([sep[, maxsplit]]) | Return a list of the words in the string, using sep as the delimiter string |
| str.join(iterable) | Concatenate any number of strings |
| len(str) | Return the length (number of characters) of the string |

### Tuples

| Command | Description |
| ------ | ------ |
| tuple.count(item) | Return the number of times x appears in the tuple |
| tuple.index(item) | Return zero-based index in the tuple of the first item whose value is equal to x |
| len(tuple) | Return the number of elements in the tuple |

### Dictionaries

| Command | Description |
| ------ | ------ |
| dict.get(key[, default]) | Return the value for key if key is in the dictionary, else default |
| dict.items() | Return a new object of the dictionary’s items in (key, value) format |
| dict.keys() | Return a new object of the dictionary’s keys |
| dict.values() | Return a new object of the dictionary’s values |
| dict.pop(key[, default]) | Remove specified key and return the corresponding value |
| dict.clear() | Remove all items from the dictionary |
| len(dict) | Return the number of items in the dictionary |

### Sets

| Command | Description |
| ------ | ------ |
| set.add(item) | Add an element to a set |
| set.remove(item) | Remove an element from a set; it must be a member |
| set.discard(item) | Remove an element from a set if it is a member |
| set.pop() | Remove and return an arbitrary set element |
| set.clear() | Remove all elements from the set |
| len(set) | Return the number of elements in the set |

### Control Flow

| Command | Description |
| ------ | ------ |
| if condition: | Checks if a condition is true |
| else: | Execute if the condition in the `if` statement is false |
| elif condition: | Checks for additional conditions if the initial `if` condition is false |
| for item in iterable: | Iterate over an iterable object |
| while condition: | Execute a block of code as long as a condition is true |
| break | Terminate the loop prematurely |
| continue | Skip the rest of the code inside a loop for the current iteration |
| pass | A null operation; nothing happens when it executes |

### Functions

| Command | Description |
| ------ | ------ |
| def function_name(parameters): | Define a function |
| return value | Return a value from a function |
| function_name(arguments) | Call a function with arguments |
| lambda parameters: expression | Create an anonymous function (lambda function) |

### Error Handling

| Command | Description |
| ------ | ------ |
| try: | Enclose code that might raise an exception |
| except ExceptionType: | Handle a specific type of exception |
| else: | Execute if the code in the `try` block doesn't raise an exception |
| finally: | Execute regardless of whether an exception was raised in the `try` block |

### File Handling

| Command | Description |
| ------ | ------ |
| open(filename, mode) | Open a file. Mode can be 'r' for read, 'w' for write, 'a' for append, 'b' for binary, '+' for read/write |
| file.read([size]) | Read the whole file or up to `size` bytes |
| file.readline() | Read the next line of the file |
| file.readlines() | Return a list of lines from the file |
| file.write(string) | Write a string to the file |
| file.close() | Close the file |

### Classes/Objects

| Command | Description |
| ------ | ------ |
| class ClassName: | Define a class |
| def __init__(self, parameters): | Define a constructor for a class |
| def method_name(self, parameters): | Define a method in a class |
| ClassName.method_name(instance, arguments) | Call a method on an instance of a class |

### Modules

| Command | Description |
| ------ | ------ |
| import module | Import a module |
| from module import name | Import a specific name from a module |
| import module as name | Import a module and give it a different name |
| module.name | Access a name from a module |

Please remember to replace `list`, `dict`, `set`, `tuple`, `str`, `ClassName`, `function_name`, `module`, `name`, `filename`, `item`, `iterable`, `condition`, `parameters`, `arguments`, `value`, `ExceptionType` with your actual values or variable names.


### List Comprehensions

| Command | Description |
| ------ | ------ |
| [expression for item in iterable] | Create a new list by applying an expression to each item in an iterable |
| [expression for item in iterable if condition] | Create a new list by applying an expression to each item in an iterable that meets a condition |

### Dictionary Comprehensions

| Command | Description |
| ------ | ------ |
| {key_expression: value_expression for item in iterable} | Create a new dictionary by applying a key/value expression to each item in an iterable |
| {key_expression: value_expression for item in iterable if condition} | Create a new dictionary by applying a key/value expression to each item in an iterable that meets a condition |

### Built-in Functions

| Command | Description |
| ------ | ------ |
| print(object) | Print an object to the console |
| input(prompt) | Get user input |
| range(start, stop[, step]) | Generate a sequence of numbers |
| len(collection) | Get the number of items in a collection |
| type(object) | Get the type of an object |
| isinstance(object, type) | Check if an object is an instance of a specific type |
| abs(number) | Get the absolute value of a number |
| max(iterable) | Get the maximum value from an iterable |
| min(iterable) | Get the minimum value from an iterable |
| sum(iterable) | Get the sum of all items in an iterable |
| sorted(iterable) | Get a new sorted list from an iterable |

### Math Functions (math module)

| Command | Description |
| ------ | ------ |
| math.sqrt(number) | Return the square root of a number |
| math.pow(base, exp) | Return base raised to the power of exp |
| math.floor(number) | Return the largest integer less than or equal to a number |
| math.ceil(number) | Return the smallest integer greater than or equal to a number |
| math.pi | Return the constant pi |
| math.e | Return the constant e |

Please remember to replace `expression`, `item`, `iterable`, `condition`, `key_expression`, `value_expression`, `object`, `prompt`, `start`, `stop`, `step`, `collection`, `type`, `number`, `base`, `exp` with your actual values or variable names.

### Generators

| Command | Description |
| ------ | ------ |
| (expression for item in iterable) | Create a new generator by applying an expression to each item in an iterable |
| yield expression | Suspend function’s execution and sends a value back to the caller, but retains enough state to enable function to resume where it left off |
| next(generator) | Retrieve the next item from a generator |

### Regular Expressions (re module)

| Command | Description |
| ------ | ------ |
| re.match(pattern, string) | Determine if the regular expression matches at the beginning of the string |
| re.search(pattern, string) | Search the string for a match to the regular expression |
| re.findall(pattern, string) | Return all non-overlapping matches of the regular expression as a list of strings |
| re.sub(pattern, replace, string) | Replace the matches of the regular expression with a different string |

### Date and Time (datetime module)

| Command | Description |
| ------ | ------ |
| datetime.datetime.now() | Get the current date and time |
| datetime.datetime(year, month, day[, hour[, minute[, second[, microsecond]]]]) | Create a new datetime object |
| datetime.timedelta(days=0, seconds=0, microseconds=0, milliseconds=0, minutes=0, hours=0, weeks=0) | Create a new timedelta object |
| datetime_object.date() | Get the date portion of a datetime object |
| datetime_object.time() | Get the time portion of a datetime object |
| datetime_object.year | Get the year portion of a datetime object |
| datetime_object.month | Get the month portion of a datetime object |
| datetime_object.day | Get the day portion of a datetime object |
| datetime_object.hour | Get the hour portion of a datetime object |
| datetime_object.minute | Get the minute portion of a datetime object |
| datetime_object.second | Get the second portion of a datetime object |
| datetime_object.microsecond | Get the microsecond portion of a datetime object |

Please remember to replace `expression`, `item`, `iterable`, `pattern`, `string`, `replace`, `generator`, `year`, `month`, `day`, `hour`, `minute`, `second`, `microsecond`, `days`, `seconds`, `microseconds`, `milliseconds`, `minutes`, `hours`, `weeks`, `datetime_object` with your actual values or variable names.

