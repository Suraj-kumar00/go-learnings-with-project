# Learning Go with building projects

<!-- This is the logo -->

<div style="text-align: center;">
    <img src="./Assets/golang.png" alt="Golang Logo" width="100" />
</div>

<!-- Here is the complete overview of this learning documentery-->

## Why write Go?

- Programming Language developed at Google `2007`
- Open-sourced in `2009`, pretty young lanugage.
- Go is natively compiled language

### Go use cases

1. Evolution of Infrastructure
2. Multi-Threading = Do multiple things at once

**Challenges of Multi-Threading**

- Multiple users editing the same document
- Multiple users booking at the same time.And yeah this should work in a way that no double booking happens (Prevent double booking)
  And this concept is called `Concurrency`: It's about dealing with lots of things at once.

  **Build-in Concurrency Mechanism**

---

- C++
- Java

- [x] Complex code
- [x] Expensive & slow

---

- Go
- [x] Go was desined to run on multiple cores and built to support concurrency
- [x] Concurrency in Go is **cheap** and **easy**

---

**No build-in Concurrency Mechanism**

- Python
- Node

#### Main Use Case of GO:

- For performant Applications
- Running on scaled, distributed systems

### Characterstics of Go

1.  Simple and readable syntax of a `dynamically typed` language like`Python`
2.  Efficiency and safety of lower-level, `statically typed language` like `C++`
3.  Server-Side or Backedn language:

- Mircrosercies
- Web applications
- Database services

4.  **Technologies that run on Go:**

- Docker
- Hashicorp **Vault**
- Kubernetes
- Cockroach DB
- and so on...

Go is becoming more and more popular for writing `simple automation applications` and `cli applications` for **DevOps** and **SRE** tasks as well.

### Execution Speed

In terms of executions speed `Go` is much faster than:

- Python
- JS
- Ruby
- PHP
  Or pretty much any `Interpreted` language is going to be slower than `Go`

### Compiled

When it comes to compilation speed, `Go` is much faster than these language.

- Rust
- C
- C++
- Java
- C#

#### VM(Vertual Machine)

Its(Go) execution speed is more similar to these language when it comes to `Runtime Speed`. A go program tends to use much less memory then:

- Java
- C#

---

### How to install Go(Golang) on Ubuntu 22.04 LTS

```bash
# update your system
sudo apt update && sudo apt upgrade

# install go
sudo apt install golang-go
```

**Install go extension if you are using VsCode:**
Extension name: `Go` official
