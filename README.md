# Concurrency in Go (Golang) — Portfolio Project

## 🚀 Overview

This project is a hands-on exploration of concurrency in Go, inspired by real professional practice and advanced coursework.  
Go’s concurrency model — built on goroutines, channels, and synchronization primitives — enables expressive and scalable solutions to problems that involve asynchronous execution and parallelism. :contentReference[oaicite:1]{index=1}

The goal of this repository is to demonstrate a practical mastery of concurrent programming in Go, including:
- Idiomatic use of goroutines and channels
- Correct synchronization with `sync.WaitGroup` and `sync.Mutex`
- Solving classical concurrency challenges
- Building real-like services using concurrent patterns
- Clean design and professional Git workflows

---

## 🧠 Key Concepts Covered

This project touches on the core tools and patterns used in high-quality Go development:

### **Concurrency Fundamentals**
- Goroutines — lightweight threads of execution
- Channels — communication between goroutines
- Synchronization with WaitGroups and Mutexes
- Avoiding common pitfalls like race conditions and deadlocks :contentReference[oaicite:2]{index=2}

### **Concurrent Design Patterns**
- Worker pools
- Fan-in / fan-out pipelines
- Controlled shutdown with context and cancellation
- Coordinating shared state safely

### **Real-World Application**
- Subscription service with asynchronous task division
- Concurrent email dispatching
- Handling user registration alongside parallel operations
- Unit and integration tests covering concurrent behavior

Each feature was implemented on its own branch with incremental commits, reflecting a real team workflow and making the project easy to follow and maintain.

---

## 📁 Project Structure

```text
.
├── cmd/                         # Main application entry points
├── internal/                    # Core business logic
│   ├── subscription/           # Subscription feature implementation
│   ├── email/                  # Concurrency in email delivery
│   ├── user/                   # User registration and plan APIs
│   └── concurrent/             # Reusable concurrency utilities
├── tests/                      # Tests validating core and concurrent logic
├── go.mod                      # Module dependencies
└── README.md                   # This documentation

## 🛠 How to Run
### 🔹 Requirements

Go 1.20+

(Optional) Docker for containerized testing

## 🔹 Run Locally
git clone https://github.com/FranciscoDev64/go-concurrency-subscription-demo.git
cd go-concurrency-subscription-demo
go run ./cmd


Replace ./cmd with the specific entrypoint if needed.

## 🧪 Testing

Tests are written with concurrency in mind. Run:

go test ./...


Tests include race detection:

go test -race ./...


This helps ensure safety against common concurrency bugs like data races.

## 🏅 Highlights

Professional Git workflow: feature branches, disciplined commits, and clean merges reflecting real software engineering standards.

Concurrency with purpose: solving classical problems and applying patterns meaningfully, not just for theory.

Modular, production-ready design: logical package separation and clarity for future extension.

This repository is not just code — it’s a demonstration of how to build reliable, maintainable, and concurrent software in Go with industry best practices.

## 📬 Contact

If you’d like to connect, you can reach me at:

Email: Francisco.dev64@gmail.com

GitHub: https://github.com/FraniscoDev64

LinkedIn: www.linkedin.com/in/franciscogonz64

## 📚 Credits

Based on concepts and patterns from “Working with Concurrency in Go (Golang)” by Trevor Sawler on Udemy — including WaitGroups, Mutexes, Channels, and real concurrency problems like producer/consumer and task coordination. 
Udemy