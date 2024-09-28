# Lessons from the Clean Code book (Robert C. Martin)

### 1. Modularity and Separation of Concerns make new decisions easy.
It is easy to restructure and add new functionalities when the concerns of the system are properly separated.

### 2. Use DSL (domain specific language) where domain persons e.g. Develops, needs to interact with the system and USL (user specific language) where a user needs to interact with the system.

### 3. While designing systems, use the simplest way/technique possible.

### 4. A testable design is a good design & a optimally testable design follows the Single Responsiblity Principle (SRP).

### 5. Reduce duplication. It makes the system more clean and managable.
Duplication can be in term of methods, implementation and classes etc.

### 6. The code should express the intent of its author.

### 7. Most likely, the next person to read your code will be you. Take pride in refining and optimizing your code once it functions correctly.

### 8. Keep the code minimal while keeping it clean and organized.

### 9. Objects are abstraction of processing, threads are abstractions of schedule.

### 10. Pay keen attention to concurrencies in the system, if present.

### 11. Some myths about Concurrency:
- Concurrency always improve performance.
- The design of the underlying system doesn't change when writting concurrent programs.
- Understanding concurrency issues is not important when working with a container such as a Web or EJB container

### 12. Realities about Concurrenty:
- Concurrency incurs some overhead, both in performance as well as writing additional code.
- Correct concurrency is complex, even for simple problems.
- Concurrency often requires a fundamental change in design strategy.

### 13. One way to decrease/overcome the difficulties of concurrenty is to apply the SRP (single responsibility principle) to it. Separate the concurrency code from the rest of the code.

### 14. Name functions as Verbs and classes as Nouns.

### 15. The name of a function or variable should reflect its purpose and how it completes that.