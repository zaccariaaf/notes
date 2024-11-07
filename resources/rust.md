# Rust
## Ownership
### Arc and Mutex
[Link](https://itsallaboutthebit.com/arc-mutex/)
- a value can have only one owner
- you can have multiple shared immutable references to a value
- you can have only one mutable reference to a value

- Arc is a smart pointer that enables sharing data between threads (atomic reference counter)
- Wraps a value and acts as a pointer to it
- Keeps track of all of the copies of the pointer
- As soon as the last pointer goes out of scope, it can safely free the memory
- Types wrapped in Arc must implement `Send` and `Sync` 
