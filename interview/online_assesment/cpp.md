C++/STL Long-Answer Questions

Explain the concept of object slicing in C++ and how to prevent it.
What is the Rule of Five? When is it needed and how does it differ from the Rule of Three?
Describe how virtual functions are implemented internally (vtable mechanism).
Compare and contrast static_cast, dynamic_cast, const_cast, and reinterpret_cast.
Explain perfect forwarding in C++ and its relationship with universal references.
What are move semantics? How do std::move and rvalue references enable them?
Describe RAII (Resource Acquisition Is Initialization) and its importance in C++.
How do smart pointers (unique_ptr, shared_ptr, weak_ptr) differ? When would you use each?
Explain SFINAE (Substitution Failure Is Not An Error) and its role in template metaprogramming.
What are C++20 concepts? How do they improve template code over SFINAE?
Compare compile-time polymorphism (templates) with runtime polymorphism (virtual functions).
Explain the CRTP (Curiously Recurring Template Pattern) and its typical use cases.
What are lambda expressions in C++? Explain capture modes and mutable lambdas.
Describe the iterator invalidation rules for vector, deque, map, and unordered_map.
Compare std::string and std::string_view. When should you prefer each?
What are allocators in STL? When would you need a custom allocator?
Explain exception safety guarantees (basic, strong, noexcept) with examples.
How does argument-dependent lookup (ADL) work? What are its advantages and pitfalls?
What is type erasure? How is it implemented in std::function?
Explain constexpr and consteval in modern C++. How do they differ from const?
Describe the template argument deduction process and how it interacts with auto.
What are fold expressions? Show how they simplify variadic template code.
Compare std::map and std::unordered_map in terms of implementation and performance.
Explain how std::initializer_list works and its role in constructor overloading.
What are transparent comparators (std::less<>) and why are they useful?

C++/STL Coding Questions

Implement a thread-safe singleton using std::call_once and std::mutex.
Write a RAII wrapper for a database connection (connect on construction, disconnect on destruction).
Create a custom array class with bounds checking and iterator support.
Implement a compile-time Fibonacci sequence calculator using constexpr.
Write a template function that works with any STL sequence container and reverses elements.
Create a move-aware matrix class demonstrating move constructor/assignment.
Implement a type-safe variant using std::variant and std::visit.
Write a template metaprogram that checks if a type is an STL associative container.
Create a factory function that perfect-forwards arguments to construct derived objects.
Implement a simple std::bind-like class that stores callables with placeholders.
Write a CRTP base class that adds cloning capability to derived classes.
Create a type traits class that detects if a type has push_back()/pop_back() methods.
Implement a compile-time string to uppercase converter using templates.
Write a custom allocator that tracks total memory allocated.
Create a template polynomial class with operator overloading (+,-,\*).
Implement a visitor pattern for a hierarchy of geometric shapes using std::variant.
Write a constexpr vector class supporting push_back at compile time.
Create a worker thread pool using std::async and std::future.
Implement a scope guard that logs when scope is exited.
Write a benchmark comparing std::list vs std::vector for insertion operations.
Create a template function that times how long a function takes to execute.
Implement a simple serialization system using templates and SFINAE.
Write a custom iterator that transforms elements from another iterator.
Create a compile-time type map with insert/find operations.
Implement a block allocator optimized for small object allocations.

C++/STL Long-Answer Questions

Explain the concept of object slicing in C++ and how to prevent it.
What is the Rule of Five? When is it needed and how does it differ from the Rule of Three?
Describe how virtual functions are implemented internally (vtable mechanism).
Compare and contrast static_cast, dynamic_cast, const_cast, and reinterpret_cast.
Explain perfect forwarding in C++ and its relationship with universal references.
What are move semantics? How do std::move and rvalue references enable them?
Describe RAII (Resource Acquisition Is Initialization) and its importance in C++.
How do smart pointers (unique_ptr, shared_ptr, weak_ptr) differ? When would you use each?
Explain SFINAE (Substitution Failure Is Not An Error) and its role in template metaprogramming.
What are C++20 concepts? How do they improve template code over SFINAE?
Compare compile-time polymorphism (templates) with runtime polymorphism (virtual functions).
Explain the CRTP (Curiously Recurring Template Pattern) and its typical use cases.
What are lambda expressions in C++? Explain capture modes and mutable lambdas.
Describe the iterator invalidation rules for vector, deque, map, and unordered_map.
Compare std::string and std::string_view. When should you prefer each?
What are allocators in STL? When would you need a custom allocator?
Explain exception safety guarantees (basic, strong, noexcept) with examples.
How does argument-dependent lookup (ADL) work? What are its advantages and pitfalls?
What is type erasure? How is it implemented in std::function?
Explain constexpr and consteval in modern C++. How do they differ from const?
Describe the template argument deduction process and how it interacts with auto.
What are fold expressions? Show how they simplify variadic template code.
Compare std::map and std::unordered_map in terms of implementation and performance.
Explain how std::initializer_list works and its role in constructor overloading.
What are transparent comparators (std::less<>) and why are they useful?

C++/STL Coding Questions

Implement a thread-safe singleton using std::call_once and std::mutex.
Write a RAII wrapper for a database connection (connect on construction, disconnect on destruction).
Create a custom array class with bounds checking and iterator support.
Implement a compile-time Fibonacci sequence calculator using constexpr.
Write a template function that works with any STL sequence container and reverses elements.
Create a move-aware matrix class demonstrating move constructor/assignment.
Implement a type-safe variant using std::variant and std::visit.
Write a template metaprogram that checks if a type is an STL associative container.
Create a factory function that perfect-forwards arguments to construct derived objects.
Implement a simple std::bind-like class that stores callables with placeholders.
Write a CRTP base class that adds cloning capability to derived classes.
Create a type traits class that detects if a type has push_back()/pop_back() methods.
Implement a compile-time string to uppercase converter using templates.
Write a custom allocator that tracks total memory allocated.
Create a template polynomial class with operator overloading (+,-,\*).
Implement a visitor pattern for a hierarchy of geometric shapes using std::variant.
Write a constexpr vector class supporting push_back at compile time.
Create a worker thread pool using std::async and std::future.
Implement a scope guard that logs when scope is exited.
Write a benchmark comparing std::list vs std::vector for insertion operations.
Create a template function that times how long a function takes to execute.
Implement a simple serialization system using templates and SFINAE.
Write a custom iterator that transforms elements from another iterator.
Create a compile-time type map with insert/find operations.
Implement a block allocator optimized for small object allocations.
