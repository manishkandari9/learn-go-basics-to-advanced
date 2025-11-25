<table width="100%">
  <tr>
     <td align="left" style="display: flex; align-items: center; gap: 10px;">
      <!-- Go Icon PNG -->
     <img 
  src="https://raw.githubusercontent.com/manishkandari9/learn-go-basics-to-advanced/main/Go.png" 
  width="50" 
  style="border-radius: 50%; border: 2px solid #00ADD8; box-shadow: 0px 2px 6px rgba(0,0,0,0.2);" 
  alt="Go Logo"
/>
    <td align="left">
      <h2 style="margin-bottom: 4px;">🟦 Learn Go (Golang) – Daily Series</h2>
      <!-- <h4 style="margin-top: 0;">Go Course Notes, Code & Progress</h4> -->
   <img
  src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=26&pause=1000&color=FFD300&center=true&vCenter=true&width=900&lines=Go%20Lang%20Series;Go%20Course%20Notes,%20Code%20%26%20Progress"
  alt="Typing SVG"
/>
    </td>
    <td align="right" width="120">
      <div>
        <img src="https://profile-counter.glitch.me/manishkandari9/count.svg?" />
      </div>
    </td>
  </tr>
</table>

<!--Table of index-->

# 📑 Table of Contents — Go Lang Daily Series

A clean, structured learning path from basics to advanced Go programming.


---

## 🟦 **01. Getting Started with Go**
- What is Go?
- Why Go? (Speed, Concurrency, Simplicity)
- Install Go (Windows / Mac / Linux)
- VS Code Setup + Extensions
- GOPATH vs GOROOT Explained
- Running Go Programs (run/build)

---

## 🟩 **02. Go Fundamentals**
- Hello World
- Comments & Formatting (gofmt)
- Variables (var, short declarations)
- Constants (iota)
- Data Types (int, float, string, bool)
- Type Conversion
- Operators (Arithmetic, Logical, Comparison)

---

## 🟨 **03. Strings & Formatting**
- String functions
- Rune vs Byte  
- String formatting (fmt.Printf, Sprintf)
- Multi-line strings

---

## 🟪 **04. Control Flow**
- if / else
- switch (value & type)
- for loops (range, conditions)
- break, continue
- defer keyword (important)

---

## 🟥 **05. Functions**
- Basic functions
- Named return values
- Multiple returns
- Variadic functions
- Anonymous functions
- Closures
- Higher-order functions

---

## 🟫 **06. Packages, Modules & Workspaces**
- What is a module?
- go.mod explained
- Importing packages
- Creating your own package
- Multi-module workspace (Go 1.18+)

---

## 🟦 **07. Core Data Structures**
- Arrays
- Slices (make, append, capacity)
- Maps (CRUD)
- Copying slices & maps
- Deep vs shallow copy

---

## 🟩 **08. Structs & Methods**
- Structs basics
- Embedding (Go’s inheritance)
- Methods (value & pointer receivers)
- Custom types
- JSON Marshalling & Unmarshalling

---

## 🟨 **09. Pointers**
- Pointer basics
- Pointer arithmetic (why Go doesn’t allow)
- Pointer receivers vs value receivers

---

## 🟪 **10. Interfaces (Go’s Polymorphism)**
- Empty interface (any)
- Type assertions
- Type switches
- Dependency injection pattern

---

## 🟥 **11. Error Handling**
- error type
- Custom errors
- Wrapping errors
- Panic, Recover
- Best error handling practices

---

## 🟫 **12. Go Generics (Go 1.18+)**
- Type parameters
- Generic functions
- Generic structs
- Constraints
- Real-use cases

---

## 🟦 **13. Concurrency (Go’s Superpower)**
- What is concurrency?
- Goroutines
- Buffered & Unbuffered Channels
- Channel directions
- Select statement
- WaitGroups
- Mutex & RWMutex
- Deadlocks & Race Conditions

---

## 🟩 **14. Advanced Concurrency Patterns**
- Fan-in / Fan-out
- Worker pools
- Pipelines
- Context cancellation
- Rate limiting
- Timeouts
- Sync package
- Atomic operations

---

## 🟨 **15. File Handling**
- Read/Write files
- Create/Delete files
- Buffer readers
- Working with JSON/YAML/TOML files

---

## 🟪 **16. Networking in Go**
- HTTP servers (net/http)
- HTTP clients
- Handling requests/responses
- Middleware patterns

---

## 🟥 **17. Building Real-world APIs**
- REST API structure
- Routing (mux, echo, gin)
- Controllers & services
- DTOs
- Validation
- Error handling patterns

---

## 🟫 **18. Databases in Go**
- SQL (MySQL, Postgres)
- Querying databases
- Prepared statements
- ORM (GORM)
- NoSQL (MongoDB driver)

---

## 🟦 **19. Testing in Go**
- Unit testing (testing package)
- Benchmarks
- Table-driven tests
- Mocking
- Coverage reports

---

## 🟩 **20. Projects & Real-World Go**
- To-do CLI tool
- Weather API
- REST API with database
- URL shortener
- Authentication system (JWT)
- Concurrency-based projects

---

## 🟨 **21. DevOps + Deployment**
- Build binaries
- Dockerizing Go apps
- Docker multi-stage builds
- Deploying to Render / Railway / EC2
- CI/CD basics

---

## 🟪 **22. Tools & Utilities**
- go vet
- go fmt
- go env
- go build / run / install
- go test
- go mod tidy

---

## 🟧 **Appendix**
- Go coding style guide
- Best practices
- Recommended books
- Official resources
- Next steps in Go

---

# 🟦 Day 1 – What is Go?

Go (Golang) is a modern programming language created at Google.  
Its development began in **2007**, and it was open-sourced in **2009**.

Go was created with one clear objective:

**Make programming simple, fast, and reliable without unnecessary complexity.**

It blends:
- the **performance & safety** of compiled languages like C/C++,  
- with the **ease & flexibility** of dynamic languages like Python.

Because of this, Go is clean, minimal, and excellent for building fast, scalable applications—especially on multi-core systems.

---

## ⭐ Why Should You Learn Go?

### 1) Beginner-Friendly  
Go is extremely easy to learn.  
Its syntax is minimal and beginner-friendly, and the tools are powerful yet simple.

### 2) Fast & Efficient  
Go compiles down to machine code.  
This makes it extremely fast—perfect for distributed systems like:

- Kubernetes  
- Docker  
- Cloudflare  

### 3) Simple but Powerful  
Go has **only 25 keywords**, yet provides powerful features like:
- interfaces  
- fast concurrency  
- strong typing  

### 4) Amazing Career Opportunities  
Go is rapidly growing across startups, cloud platforms, DevOps tools, and enterprises.  
Go developers are highly in demand with strong salaries.

### Popular use cases:
- Backend systems  
- Microservices  
- DevOps tooling  
- Cloud engineering  
- High-performance systems  

---

## ⭐ Why Go Was Created  

Go was created to fix limitations in older languages:

1. **Slow compilation** (like C++)  
2. **Overly complex codebases**  
3. **Weak concurrency models**

Go solves these problems by offering:
- very fast compilation  
- clean & readable syntax  
- built-in concurrency (goroutines)  
- single-binary deployment  

---

## 🟨 Key Features of Go

- **Simple syntax** (only 25 keywords)  
- **C-level performance**  
- **Memory efficient**  
- **Built-in concurrency (goroutines)**  
- **Easy deployment (single binary)**  
- **Cross-platform builds**  

---

## 🟩 Where is Go Used?

Some of the world’s most powerful tools are written in Go:

- Docker  
- Kubernetes  
- Grafana  
- Terraform  
- Cloudflare  
- Uber’s backend  

Go is the top choice for:
- DevOps  
- Cloud systems  
- Distributed systems  
- Scalable backends  

---

## 🟩 Ready to Begin?

This marks the official start of your Go learning journey.  
Let's continue building — step by step.



### 🔔 New topics + daily content updates will be added automatically.

