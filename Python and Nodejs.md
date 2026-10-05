# ⚡ Python Rapid Fire — 50 Questions & One-Line Answers

## 1. Variables & Data Types

1. What is Python?  
   → A high-level, dynamically typed, general-purpose programming language.

2. What is a variable in Python?  
   → A name that refers to an object.

3. Is Python statically or dynamically typed?  
   → Dynamically typed.

4. Is Python strongly typed?  
   → Yes, Python is generally considered strongly typed.

5. What is an object?  
   → A runtime entity containing a value, type, and identity.

6. What are the main built-in data types?  
   → int, float, complex, bool, str, list, tuple, set, dict, and NoneType.

7. What is None?  
   → A special object representing the absence of a value.

8. What is type conversion?  
   → Converting a value from one data type to another.

9. What does input() return?  
   → A string.

10. What does type() do?  
   → Returns the type of an object.

---

## 2. Operators

11. What is an operator?  
   → A symbol or keyword that performs an operation on operands.

12. What is =?  
   → Assignment operator.

13. What is ==?  
   → Equality comparison operator.

14. What is the difference between == and is?  
   → == compares values; is compares object identity.

15. What does / do?  
   → Performs division and normally returns a float.

16. What does // do?  
   → Performs floor division.

17. What does % do?  
   → Returns the remainder.

18. What does ** do?  
   → Performs exponentiation.

19. What is short-circuit evaluation?  
   → Python stops evaluating a logical expression when the result is already known.

20. What do and and or return?  
   → They return one of their operands, not necessarily a Boolean.

---

## 3. Functions

21. What is a function?  
   → A reusable block of code designed to perform a specific task.

22. How do you define a function?  
   → Using the def keyword.

23. What is a parameter?  
   → A variable defined in a function declaration.

24. What is an argument?  
   → A value passed to a function when calling it.

25. What does return do?  
   → Sends a value back to the caller.

26. What does a function return without return?  
   → None.

27. What is a default parameter?  
   → A parameter with a predefined value.

28. What is *args?  
   → It collects variable positional arguments into a tuple.

29. What is **kwargs?  
   → It collects variable keyword arguments into a dictionary.

30. Are functions first-class objects in Python?  
   → Yes, functions can be stored, passed, and returned like other objects.

---

## 4. Memory & References

31. What is object identity?  
   → The unique identity of an object during its lifetime.

32. How do you check an object’s identity?  
   → Using id().

33. What does is check?  
   → Whether two names refer to the same object.

34. What does == check?  
   → Whether two objects are equal in value.

35. What is a mutable object?  
   → An object whose contents can be changed after creation.

36. Give examples of mutable types.  
   → list, dict, and set.

37. Give examples of immutable types.  
   → int, float, str, tuple, and bool.

38. Are variables mutable or immutable?  
   → Neither; mutability is a property of objects.

39. What is reference counting?  
   → A CPython memory-management technique that tracks references to objects.

40. Why does Python need garbage collection?  
   → To handle unreachable objects, including reference cycles that reference counting alone cannot clean up.

---

## 5. Interview Traps

41. What happens with a = b when b is a list?  
   → Both names refer to the same list object.

42. What happens when you modify that list through a?  
   → The change is visible through b because both reference the same object.

43. Does a = a + [1] modify the original list?  
   → No, it creates a new list and rebinds a.

44. Does a.append(1) modify the original list?  
   → Yes, append() mutates the existing list.

45. What is a mutable default argument problem?  
   → A mutable default value is reused across function calls.

46. What is LEGB?  
   → Local, Enclosing, Global, and Built-in name lookup order.

47. What is a reference cycle?  
   → A situation where objects reference each other in a cycle.

48. Can Python have memory leaks despite garbage collection?  
   → Yes, if unwanted objects remain reachable.

49. What is the difference between stack and heap?  
   → Stack-like execution frames manage calls, while objects are generally managed in heap memory; exact implementation varies.

50. What is the most important rule when explaining Python internals?  
   → Distinguish Python language behavior from CPython implementation details.

---

# ⚡ Python vs Node.js — 50 Yes/No Rapid Fire

1. Is Python dynamically typed?  
   Answer: Yes  
   Reason: Python determines variable types at runtime, so you do not need to declare them explicitly.

2. Is Node.js a programming language?  
   Answer: No  
   Reason: Node.js is a JavaScript runtime environment, not the JavaScript language itself.

3. Is Node.js a JavaScript runtime?  
   Answer: Yes  
   Reason: Node.js runs JavaScript code outside the browser using the V8 engine.

4. Is Python strongly typed?  
   Answer: Yes  
   Reason: Python prevents implicit type changes in many cases, so values must respect their types.

5. Is JavaScript dynamically typed?  
   Answer: Yes  
   Reason: JavaScript variables can hold different types during execution without explicit declaration.

6. Does Node.js use the V8 engine?  
   Answer: Yes  
   Reason: Node.js is built on Chrome’s V8 engine, which executes JavaScript.

7. Does CPython compile source code to bytecode?  
   Answer: Yes  
   Reason: CPython translates Python source into bytecode before executing it.

8. Does Node.js use an event loop?  
   Answer: Yes  
   Reason: The event loop handles asynchronous operations without blocking the main thread.

9. Does normal synchronous Python code automatically use an event loop?  
   Answer: No  
   Reason: Regular Python code runs without an event loop unless async features are used.

10. Can Python perform asynchronous programming?  
   Answer: Yes  
   Reason: Python supports async/await for non-blocking operations and task scheduling.

11. Can Node.js perform asynchronous programming?  
   Answer: Yes  
   Reason: Node.js is designed around async callbacks, promises, and the event loop.

12. Is def used to define a Python function?  
   Answer: Yes  
   Reason: The def keyword is used to create a function in Python.

13. Is function required to define every JavaScript function?  
   Answer: No  
   Reason: JavaScript supports function expressions, arrow functions, and methods without a def keyword.

14. Are Python functions first-class objects?  
   Answer: Yes  
   Reason: Functions in Python can be assigned, passed, and returned like other objects.

15. Are JavaScript functions first-class objects?  
   Answer: Yes  
   Reason: Functions in JavaScript are values and can be passed around like objects.

16. Is None a Python value?  
   Answer: Yes  
   Reason: None is the Python equivalent of “no value” or “null-like” absence.

17. Is None the same as JavaScript null?  
   Answer: No  
   Reason: Python None and JavaScript null are different language-specific values, even though they serve similar purposes.

18. Does Python have is for identity comparison?  
   Answer: Yes  
   Reason: is checks whether two names refer to the same object in memory.

19. Does JavaScript have Python’s is operator?  
   Answer: No  
   Reason: JavaScript uses === for strict equality and does not have Python’s identity operator.

20. Does === perform strict equality in JavaScript?  
   Answer: Yes  
   Reason: === compares both value and type, so 5 and "5" are not equal.

21. Does Python use == for value equality?  
   Answer: Yes  
   Reason: == compares value equality for most objects.

22. Does Python use == for object identity?  
   Answer: No  
   Reason: Identity is checked using is, not ==.

23. Does Python have a GIL in standard CPython builds?  
   Answer: Yes  
   Reason: CPython includes the GIL, which limits true parallel execution of threads in some cases.

24. Does Node.js have Python’s GIL?  
   Answer: No  
   Reason: Node.js does not use Python’s GIL model; it uses a single-threaded event loop.

25. Can CPU-heavy JavaScript block Node’s main event loop?  
   Answer: Yes  
   Reason: Intensive CPU work can delay the event loop, preventing other tasks from running promptly.

26. Can Python use multiple processes for CPU-bound work?  
   Answer: Yes  
   Reason: Python can use multiprocessing to distribute heavy workloads across cores.

27. Can Node.js use multiple processes?  
   Answer: Yes  
   Reason: Node.js can run multiple processes or workers for scalability and CPU-heavy tasks.

28. Can Node.js use worker threads?  
   Answer: Yes  
   Reason: Worker threads allow JavaScript code to run in parallel for certain workloads.

29. Does Python automatically garbage-collect memory?  
   Answer: Yes  
   Reason: Python uses garbage collection to reclaim memory from unreachable objects.

30. Does Node.js automatically garbage-collect memory?  
   Answer: Yes  
   Reason: V8 manages memory automatically through garbage collection.

31. Does CPython use reference counting?  
   Answer: Yes  
   Reason: CPython tracks object references to clean up objects quickly when no references remain.

32. Does V8 use garbage collection?  
   Answer: Yes  
   Reason: V8 uses garbage collection to reclaim unused heap memory.

33. Can both Python and Node.js applications have memory leaks?  
   Answer: Yes  
   Reason: Poor object retention or unmanaged references can cause leak-like behavior in either environment.

34. Does garbage collection guarantee that all unused memory is immediately returned to the OS?  
   Answer: No  
   Reason: Garbage collection frees memory for reuse, but not always immediately back to the operating system.

35. Is a Python list mutable?  
   Answer: Yes  
   Reason: Lists can change their contents after creation.

36. Is a JavaScript Array mutable?  
   Answer: Yes  
   Reason: Arrays can add, remove, or update elements after creation.

37. Is a Python string mutable?  
   Answer: No  
   Reason: Python strings are immutable; changing them creates a new string object.

38. Is a JavaScript string mutable?  
   Answer: No  
   Reason: JavaScript strings are immutable; operations create new strings rather than changing the original.

39. Is Python’s dict similar to a JavaScript object for many use cases?  
   Answer: Yes  
   Reason: Both store key-value pairs and are commonly used for mappings.

40. Does Python use pip for package management?  
   Answer: Yes  
   Reason: pip installs and manages Python packages from the Python ecosystem.

41. Does Node.js commonly use npm for package management?  
   Answer: Yes  
   Reason: npm is the standard package manager for Node.js projects.

42. Does Python have try/except?  
   Answer: Yes  
   Reason: Python handles exceptions using try and except blocks.

43. Does JavaScript have try/catch?  
   Answer: Yes  
   Reason: JavaScript uses try/catch to handle exceptions.

44. Does Python use raise to explicitly raise an exception?  
   Answer: Yes  
   Reason: raise is used to trigger a custom or built-in exception in Python.

45. Does JavaScript use throw to explicitly throw an exception?  
   Answer: Yes  
   Reason: JavaScript throws exceptions with the throw keyword.

46. Can Python be used to build REST APIs?  
   Answer: Yes  
   Reason: Frameworks like Flask and Django are commonly used for REST APIs.

47. Can Node.js be used to build REST APIs?  
   Answer: Yes  
   Reason: Node.js is widely used to build fast web APIs and backend services.

48. Is Node.js particularly suited to I/O-heavy applications?  
   Answer: Yes  
   Reason: Its non-blocking event loop makes it efficient for network and file I/O.

49. Is Python only useful for AI and data science?  
   Answer: No  
   Reason: Python is also used for web development, automation, scripting, and backend services.

50. Can both Python and Node.js be used for backend development?  
   Answer: Yes  
   Reason: Both are popular choices for server-side application development.