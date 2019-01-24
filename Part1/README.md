# Mutex and Channel basics

### What is an atomic operation?
> An atomic operation is an operation that run independantly of all other operations.

### What is a semaphore?
> A semaphore is a variable that controls access to a common resource. 

### What is a mutex?
> A mutex is a property that prevents race conditions. Only the thread that holds
the mutex can access the resource, other threads can request to get the mutex.

### What is the difference between a mutex and a binary semaphore?
> A mutex can only be opened by the thread that locked the mutex. 

### What is a critical section?
> A critical section is the part of a program where the thread accesses shared
variables. Race conditions can be avoided if no more than one thread is in a critical 
section at the same time. 

### What is the difference between race conditions and data races?
> Race conditions is affecting the correctness of the program. This by executing
different parts of the programming in wrong order. A data race occures when two threads are trying 
to access the same memory position at the same time. 

### List some advantages of using message passing over lock-based synchronization primitives.
> Koden blir mindre innviklet. Det er lettere å se hva som avhenger av hva.

### List some advantages of using lock-based synchronization primitives over message passing.
> 