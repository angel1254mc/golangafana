# Overview
Here, I'll be writing down notes on the overview section of the Go course by TechWorld with Nana B-)

## Its Creation
- Developed in Google in 2007
- Open-Sourced later in 2009

**But why make a new language?**
- Infrastructure was becoming more scalable and more dynamic, and more things could be done in parallel.

However, a lot of languages didn't exploit the parallelism capabilities of modern systems.
(goroutines foreshadowing)

It would be nice to have a language with a built-in concurrency mechanism that is easy to use (do Promises technically count as concurrency mechanisms or naw?)

**Go was meant for this**
- designed to run on multiple cores with built-in concurrency mechanism
- relatively cheap and easy to use

**Use Cases of Go**
- performant applications
- applications that make use of distributed architecture

Go compiles into a single binary that can be run accross different platforms/operating systems.