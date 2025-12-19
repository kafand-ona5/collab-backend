# Phase 0 – Foundations

## Concurrency vs Parallelism
- Concurrency: ability to make progress on multiple tasks at overlapping times
- Parallelism: multiple tasks executing at the same time on multiple cores

## Threads
- Smallest schedulable unit of execution
- Share memory space, risks: data races, deadlocks

## Async & Event Loops
- Non-blocking I/O
- Event-driven, often single-threaded

## Synchronization
- std::mutex: heavy, locks critical sections
- std::atomic: lightweight, lock-free for simple operations

## Networking
- TCP: reliable, ordered, error-checked protocol
- WebSockets: persistent, full-duplex for real-time communication

## Consistency & CRDTs
- Eventual consistency in distributed systems
- CRDTs enable conflict-free collaboration

## Security
- JWT authentication
- Password hashing (bcrypt/argon2)
