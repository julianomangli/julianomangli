# Juliano Mangli — Technical Knowledge & Development Profile

<p align="center">
  <img src="https://streak-stats.demolab.com?user=julianomangli&theme=github-dark&hide_border=true" height="150" alt="GitHub streak" />
</p>

---

## About this profile

This README is a structured map of the technologies, tools, environments, platforms, and concepts I have worked with or studied.

Instead of listing technology names without context, I describe **what each technology is, what problem it solves, where it belongs in a software stack, and how I understand its role in real development**.

My main areas of interest are:

* Full-stack web development
* Local-first and privacy-focused applications
* IT support and technical operations
* Automation and scripting
* Game development
* Linux and system administration
* Networking and security fundamentals
* Databases and APIs
* Cloud, deployment, containers, and CI/CD
* Software architecture and developer tooling

> **Important:** This is a knowledge map, not a claim that every technology below is used at the same depth. Some are technologies I actively build with, while others represent broader hands-on exposure, experimentation, study, or foundational knowledge.

---

# Core Web Development

## HTML

**HTML — HyperText Markup Language** is the structural language of the web.

It describes the semantic content of webpages: headings, paragraphs, navigation, links, forms, images, media, tables, and application containers.

HTML is the **document structure layer** of a web application.

Good HTML also matters for:

* Accessibility
* SEO
* Forms
* Browser behavior
* Keyboard navigation
* Semantic document structure
* Maintainable frontend development

---

## CSS

**CSS — Cascading Style Sheets** controls the presentation of HTML.

CSS handles:

* Layout
* Typography
* Colors
* Spacing
* Responsive design
* Flexbox
* CSS Grid
* Positioning
* Animations
* Transitions
* Media queries
* Visual component states

HTML provides the structure; CSS controls how that structure is visually presented.

---

## JavaScript

**JavaScript** is the primary programming language used to create interactive behavior on the web.

Inside browsers it can control:

* User interactions
* DOM elements
* Forms
* Application state
* API requests
* Animations
* Dynamic page content

With Node.js, JavaScript can also run outside the browser and power backend servers, scripts, automation, developer tooling, and APIs.

Important concepts include:

* Variables
* Functions
* Objects
* Arrays
* Modules
* Events
* Promises
* `async/await`
* Error handling
* HTTP requests
* DOM manipulation

---

## TypeScript

**TypeScript** extends JavaScript by adding static type checking.

It helps detect many programming mistakes before the application executes.

Important TypeScript concepts include:

* Primitive types
* Interfaces
* Type aliases
* Generics
* Union types
* Intersection types
* Type narrowing
* Typed functions
* Typed objects
* Typed API contracts

TypeScript becomes especially valuable as JavaScript projects become larger and contain many components, APIs, database models, and shared structures.

---

## Tailwind CSS

**Tailwind CSS** is a utility-first CSS framework.

Instead of creating a custom CSS class for every component, Tailwind provides reusable utility classes representing styling rules.

It is useful for:

* Responsive design
* Spacing
* Typography
* Flexbox
* Grid
* Colors
* Borders
* Dark mode
* Component systems
* Fast UI prototyping

I use Tailwind when I want to move quickly while maintaining a consistent visual system.

---

# Frontend Frameworks

## React

**React** is a JavaScript library for creating user interfaces from reusable components.

A React application is divided into independent pieces such as:

* Navigation bars
* Product cards
* Forms
* Modals
* Dashboards
* Chat messages
* Media players
* Settings panels

Important React concepts include:

* Components
* Props
* State
* Hooks
* Events
* Conditional rendering
* Lists
* Context
* Component composition

React's component architecture allows complex interfaces to be divided into smaller systems that are easier to develop and maintain.

---

## Next.js

**Next.js** is a full-stack framework built around React.

It adds functionality that React alone does not provide as a complete application framework.

Features include:

* Routing
* Layouts
* Server-side rendering
* Static generation
* React Server Components
* Client Components
* Server functionality
* Route handlers
* Middleware
* Metadata
* Image optimization
* Production builds

I use Next.js when an application needs frontend and server responsibilities in one structured project.

---

## Vite

**Vite** is a modern frontend development and build tool.

It provides:

* A fast development server
* Hot module replacement
* TypeScript support
* Modern module handling
* Optimized production builds

A Vite project may run locally at an address such as:

`http://localhost:5173`

It is particularly useful for React applications where I want fast local iteration without requiring the complete Next.js framework.

---

## TanStack Query

**TanStack Query** manages remote server state inside frontend applications.

It helps with:

* API requests
* Caching
* Loading states
* Automatic refetching
* Mutations
* Error states
* Cache invalidation
* Request deduplication

This is useful when an application depends heavily on live backend data.

---

# Backend Development

## Node.js

**Node.js** is a JavaScript runtime based on Google's V8 JavaScript engine.

It allows JavaScript to run outside the browser.

Node.js can power:

* Backend servers
* REST APIs
* WebSocket services
* Command-line programs
* Build tools
* Automation
* File processing
* Development servers

Important concepts include:

* The event loop
* Asynchronous I/O
* Processes
* Environment variables
* Filesystem APIs
* Modules
* HTTP servers
* Package management

---

## Express.js

**Express** is a lightweight web framework for Node.js.

It simplifies creating HTTP servers and APIs.

Express can handle:

* Routes
* Requests
* Responses
* Middleware
* Authentication checks
* Validation
* API endpoints
* Error handling
* Static files

Example architecture:

`Browser → Express API → Application logic → Database`

---

## Python

**Python** is a general-purpose programming language known for readable syntax and a very large software ecosystem.

I use or study Python for:

* Automation
* System utilities
* Backend APIs
* Data processing
* File manipulation
* Local software
* Networking
* Security tooling
* AI-related development

---

## FastAPI

**FastAPI** is a Python framework for building HTTP APIs.

It uses Python type annotations to provide:

* Request validation
* Response validation
* API schemas
* Automatic documentation
* Async endpoint support
* Integration with Pydantic

Typical structure:

`Frontend → FastAPI → Pydantic validation → application logic → database/files`

---

## Pydantic

**Pydantic** is a Python data validation system based on Python type annotations.

It can define exactly what application data should look like.

This is useful for validating:

* API requests
* API responses
* Configuration
* Database-facing objects
* User input

---

# APIs

## REST APIs

A **REST API** is a common architecture for communication between software systems over HTTP.

Common methods include:

* `GET` — retrieve information
* `POST` — create information
* `PUT` — replace information
* `PATCH` — partially update information
* `DELETE` — remove information

An API acts as a contract between systems.

The frontend does not need to understand the internal backend implementation as long as both agree on the API contract.

---

## JSON

**JSON — JavaScript Object Notation** is a lightweight structured-data format.

Example:

```json
{
  "username": "julianomangli",
  "online": true
}
```

JSON is commonly used for:

* API responses
* API requests
* Configuration
* Local storage
* Application data
* Service integration

---

## GraphQL

**GraphQL** is an API query language and runtime.

Unlike many REST APIs where endpoints return predefined structures, GraphQL allows clients to request specific fields through a schema.

Core concepts include:

* Schema
* Types
* Queries
* Mutations
* Resolvers
* Nested relationships

---

# Services & Integrations

## Stripe

**Stripe** is payment infrastructure for software applications.

A proper Stripe integration can involve:

* Products
* Prices
* Checkout Sessions
* Payment Intents
* Customers
* Webhooks
* Subscriptions
* Payment verification

Stripe also introduces an important security concept:

**secret API keys belong on the server and must never be exposed in frontend code.**

---

## Printful

**Printful** is a print-on-demand and fulfillment service.

Software can integrate with Printful to manage:

* Products
* Product variants
* Sizes
* Colors
* Mockups
* Orders
* Fulfillment
* Shipping information

It allows an e-commerce frontend to connect to a physical product fulfillment system.

---

## Sanity

**Sanity** is a headless content-management system.

A headless CMS separates content storage/editing from the frontend that displays it.

Content can therefore be managed once and used by:

* Websites
* React applications
* Next.js applications
* Mobile applications
* Other API clients

---

# Databases

## PostgreSQL

**PostgreSQL** is an open-source relational database management system.

Data is stored using structures such as:

* Tables
* Rows
* Columns
* Relationships
* Constraints
* Indexes

PostgreSQL also provides:

* Transactions
* SQL queries
* Foreign keys
* Strong consistency
* Advanced database functionality

It is suitable for structured application data such as users, products, orders, permissions, and messages.

---

## MySQL

**MySQL** is another widely used relational database.

Like PostgreSQL, it uses SQL and stores structured data in relational tables.

It is common in:

* Web applications
* Content management
* Business applications
* Backend systems

---

## SQLite

**SQLite** is a lightweight relational database contained inside a file.

Unlike PostgreSQL or MySQL, a separate database server does not normally need to run.

This makes SQLite useful for:

* Desktop applications
* Local-first software
* Offline applications
* Small private systems
* Development
* Prototypes

For my local-first projects, this model is especially useful because the data can remain directly on the user's machine.

---

## MongoDB

**MongoDB** is a document-oriented NoSQL database.

Rather than traditional SQL rows, it stores JSON-like BSON documents inside collections.

It is useful where application information fits naturally into flexible document structures.

---

## Firebase

**Firebase** is Google's backend-as-a-service platform.

Its ecosystem can provide:

* Authentication
* Firestore
* Realtime Database
* Cloud Storage
* Cloud Functions
* Hosting
* Analytics

Firebase allows applications to use managed backend infrastructure instead of building every server component independently.

---

# ORM Technologies

## Prisma

**Prisma** is an ORM and database toolkit commonly used in JavaScript and TypeScript applications.

ORM means **Object Relational Mapper**.

Prisma provides:

* Database schemas
* Migrations
* Generated database clients
* Relationships
* Typed queries

An ORM improves development productivity, but developers still benefit from understanding SQL and the underlying database.

---

## Drizzle ORM

**Drizzle** is a TypeScript ORM and SQL toolkit.

It emphasizes:

* Type safety
* SQL-like structure
* Explicit schemas
* Relational database access

It acts as a bridge between TypeScript application code and relational databases.

---

# Version Control

## Git

**Git** is a distributed version-control system.

It records changes to source code over time.

Important concepts include:

* Repository
* Commit
* Branch
* Merge
* Rebase
* Remote
* Clone
* Pull
* Push
* Staging
* `.gitignore`
* Conflict resolution

Git makes it possible to experiment without losing stable versions of a project.

---

## GitHub

**GitHub** hosts Git repositories and adds collaboration and project-management features.

These include:

* Pull requests
* Issues
* Code review
* Repository hosting
* Releases
* GitHub Actions
* Branch protection
* Permissions
* Documentation
* Public developer portfolios

I use GitHub both as development infrastructure and as a way to document my projects and knowledge.

---

# CI/CD

## GitHub Actions

**GitHub Actions** is GitHub's automation and CI/CD platform.

A workflow can automatically perform actions after:

* A push
* A pull request
* A release
* A schedule
* A manual trigger

Typical workflow:

`code → push → install → lint → test → build → deploy`

Actions can automate:

* Testing
* Linting
* Builds
* Deployments
* Artifact creation
* Releases

---

## CI/CD

**CI/CD** stands for Continuous Integration and Continuous Delivery/Deployment.

Continuous Integration checks whether new code integrates safely.

Continuous Delivery/Deployment automates the preparation or release of application changes.

The purpose is to make software releases reproducible rather than dependent entirely on manual procedures.

---

# Docker & Containers

## Docker

**Docker** is a containerization platform.

A Docker container packages an application together with the environment it expects.

Important concepts include:

* Images
* Containers
* Dockerfiles
* Volumes
* Ports
* Networks
* Environment variables
* Registries
* Docker Compose

A container is not simply another name for a virtual machine.

Containers normally share the host operating-system kernel while isolating application processes and filesystem environments.

---

# Deployment

## Vercel

**Vercel** is a cloud deployment platform focused heavily on modern web applications and Next.js.

It can provide:

* Git-based deployments
* Production deployments
* Preview deployments
* Environment variables
* Build execution
* Domains
* Serverless functions
* Edge functionality
* Deployment logs

---

## GitHub Pages

**GitHub Pages** hosts static websites directly from GitHub repositories.

It works well for:

* Documentation
* HTML/CSS/JavaScript websites
* Portfolio pages
* Static generated websites

It does not operate like a traditional always-running backend server.

---

# Development Environments

## localhost

**localhost** refers to the current computer.

It normally resolves through the loopback network interface:

`127.0.0.1`

Example:

`http://localhost:5173`

means:

> connect to port 5173 on this same computer.

---

## LAN

**LAN — Local Area Network** is the private network connecting devices in a local environment such as a home.

A development server can listen on an address such as:

`192.168.1.x`

allowing devices connected to the same network to open it.

Examples include:

* Laptop → phone
* Laptop → tablet
* Laptop → another PC
* Laptop → browser-capable television/device

A LAN-exposed development server requires more security consideration than a localhost-only service.

---

## Environment Variables

**Environment variables** store configuration outside normal application source code.

They can contain:

* API locations
* Database URLs
* Feature switches
* Runtime configuration
* Secret keys

Sensitive `.env` files should normally not be committed to public repositories.

A safe pattern is:

```text
.env
.env.local
```

inside `.gitignore`, while providing:

```text
.env.example
```

with placeholder values.

---

## Development vs Production

A **development environment** prioritizes:

* Debugging
* Hot reload
* Detailed errors
* Fast iteration

A **production environment** prioritizes:

* Security
* Reliability
* Optimized builds
* Correct configuration
* Monitoring
* Performance

Something working on localhost does not automatically mean it is safe or correctly configured for public production use.

---

# Developer Tools

## Visual Studio Code

**Visual Studio Code** is a source-code editor.

I use it for:

* Code editing
* Project navigation
* Integrated terminals
* Git
* Debugging
* Search
* Refactoring
* Extensions
* Formatting
* Linting

---

## Replit

**Replit** is a browser-based programming environment.

It allows code to be developed and executed without requiring the complete development environment to exist locally.

It is useful for:

* Experiments
* Prototypes
* Learning
* Collaborative development
* Browser-accessible coding

---

## npm

**npm** is the package manager distributed with Node.js.

It manages JavaScript dependencies and project scripts.

Common files include:

`package.json`

which describes the project and dependencies, and:

`package-lock.json`

which records exact dependency versions for reproducibility.

---

## Bun

**Bun** is a JavaScript and TypeScript runtime/toolkit.

Its ecosystem combines functionality including:

* Runtime
* Package manager
* Bundler
* Test runner

It aims to provide a fast integrated JavaScript toolchain.

---

## ESLint

**ESLint** performs static analysis of JavaScript and TypeScript.

It can detect:

* Problematic patterns
* Likely bugs
* Inconsistent code
* Unsafe constructs
* Style problems

It catches many problems before the code is executed.

---

## Markdown

**Markdown** is a lightweight markup language designed for readable documentation.

GitHub uses Markdown extensively for:

* README files
* Issues
* Pull requests
* Documentation
* Discussions

This README itself is written in Markdown.

---

# Operating Systems

## Windows

Windows is both an everyday desktop operating system and an important IT-support/development environment.

Areas I work with include:

* System configuration
* Application installation
* Troubleshooting
* Hardware and peripherals
* Processes
* Services
* Networking
* PowerShell
* Development tooling

---

## Linux

**Linux** is an open-source operating-system kernel used by many distributions, servers, containers, embedded systems, and cloud platforms.

Core concepts include:

* Filesystem hierarchy
* Permissions
* Users
* Groups
* Processes
* Services
* Shells
* Package managers
* Networking
* SSH
* Logs

Linux knowledge is directly useful for server and cloud development.

---

## Ubuntu

**Ubuntu** is a Debian-based Linux distribution.

It is widely used for:

* Desktop Linux
* Development
* Servers
* Virtual machines
* Cloud infrastructure

Its package-management ecosystem uses APT.

---

## Kali Linux

**Kali Linux** is a Debian-based distribution built primarily for penetration testing, security research, and digital forensics.

The tools themselves are only part of security work.

Understanding:

* Networks
* Protocols
* Operating systems
* HTTP
* Authentication
* Permissions
* Vulnerabilities

is more important than simply installing penetration-testing software.

Security tools should only be used against systems owned by the tester or where explicit authorization exists.

---

## Fedora

**Fedora** is a Linux distribution associated with the Red Hat ecosystem.

It often introduces newer Linux technologies relatively early and uses RPM/DNF package management.

---

## Arch Linux

**Arch Linux** is a rolling-release Linux distribution emphasizing user control and manual configuration.

Working with Arch can provide deeper exposure to how Linux components are installed and configured.

---

# Shells & Automation

## Bash

**Bash — Bourne Again Shell** is a shell and scripting language widely used on Linux and Unix-like operating systems.

It can automate:

* File manipulation
* Build processes
* System commands
* Server operations
* Text processing
* Development tasks

---

## PowerShell

**PowerShell** is Microsoft's command shell and automation language.

Unlike many traditional shells that primarily exchange text, PowerShell pipelines can pass structured objects.

It is powerful for:

* Windows administration
* Files
* Processes
* Services
* Networking
* Automation
* Microsoft infrastructure

---

# Networking

## IP Addresses

An **IP address** identifies a network interface participating in an IP network.

Private address ranges such as:

`192.168.x.x`

are commonly used inside home networks.

Public addresses allow communication across the wider internet.

---

## Ports

A **port** identifies a particular network service on a machine.

One machine can have a single IP address while many services use different ports.

This explains URLs such as:

```text
localhost:3000
localhost:5173
localhost:8787
```

Each port can represent a separate service.

---

## TCP

**TCP — Transmission Control Protocol** provides reliable, ordered communication between systems.

TCP detects missing data and provides sequencing and retransmission behavior.

---

## UDP

**UDP — User Datagram Protocol** is connectionless and has lower protocol overhead.

It does not guarantee delivery or ordering by itself.

Applications choose between TCP and UDP depending on the required protocol characteristics.

---

## DNS

**DNS — Domain Name System** converts human-readable domain names into network information such as IP addresses.

Without DNS, users would frequently need to remember numerical server addresses instead of domain names.

---

## HTTP

**HTTP — Hypertext Transfer Protocol** is the communication protocol underlying the web.

Important concepts include:

* Requests
* Responses
* Methods
* Headers
* Status codes
* Cookies
* Caching

---

## HTTPS

**HTTPS** is HTTP protected through TLS encryption.

Correct HTTPS provides:

* Encryption
* Data integrity
* Server authentication

This prevents normal network observers from simply reading application content in transit.

---

## WebSockets

**WebSocket** creates a persistent bidirectional connection between a client and server.

After connecting, both client and server can send messages.

Useful applications include:

* Messaging
* Live dashboards
* Presence indicators
* Multiplayer systems
* Notifications
* Collaborative applications

---

# Security & Ethical Hacking

My interest in security focuses on legitimate testing, defensive understanding, troubleshooting, labs, and systems where I have authorization.

---

## Nmap

**Nmap — Network Mapper** performs network discovery and port scanning.

It can help identify:

* Reachable machines
* Open ports
* Network services
* Some service characteristics

From a defensive perspective, it answers an important question:

> What is my machine exposing to the network?

---

## Wireshark

**Wireshark** is a network protocol analyzer.

It captures and decodes packets.

It can help with:

* Network troubleshooting
* Protocol learning
* DNS debugging
* Client/server debugging
* HTTP analysis
* Packet inspection

---

## Burp Suite

**Burp Suite** is a web application security testing platform.

Its intercepting proxy allows an authorized tester to inspect HTTP traffic between a browser and web application.

It helps understand:

* Requests
* Responses
* Cookies
* Sessions
* Headers
* Authentication
* APIs
* Web application behavior

---

## Metasploit Framework

**Metasploit Framework** is a penetration-testing framework.

It organizes modules used for controlled vulnerability validation and security research.

It should be used in authorized systems and lab environments.

The framework itself is less important than understanding the vulnerability or protocol being tested.

---

## Aircrack-ng

**Aircrack-ng** is a suite of wireless-network security tools.

It is used for authorized Wi-Fi monitoring, capture, analysis, and authentication security testing.

---

# Game Development

## Unreal Engine 5

**Unreal Engine 5** is a real-time 3D development engine.

It is used for:

* Games
* Simulations
* Visualization
* Virtual production
* Interactive 3D applications

Important Unreal areas include:

* Actors
* Components
* Levels
* Worlds
* Physics
* Animation
* Materials
* Lighting
* Niagara
* UI
* AI
* Blueprints
* C++

---

## Unreal Blueprints

**Blueprints** are Unreal Engine's visual programming system.

Programming logic is represented using interconnected nodes.

Blueprints are particularly useful for:

* Prototyping
* Gameplay events
* Level scripting
* Interactive systems
* Designer-facing logic

---

## C++ with Unreal

**C++** is Unreal Engine's primary native programming language.

It can be used for:

* Gameplay architecture
* Performance-sensitive systems
* Engine integration
* Reusable components
* Complex systems

Unreal also adds engine-specific concepts such as:

* `UObject`
* `AActor`
* `UActorComponent`
* Reflection
* Garbage collection
* Replication
* Engine modules

---

## Unity

**Unity** is a cross-platform real-time engine.

It is used for:

* 2D games
* 3D games
* Mobile games
* Desktop applications
* VR/AR
* Simulations

Important concepts include:

* Scenes
* GameObjects
* Components
* Prefabs
* Physics
* Animation
* UI
* Input
* Materials

---

## C# with Unity

**C#** is Unity's primary scripting language.

It is used for:

* Gameplay systems
* Components
* Player control
* UI
* State management
* Procedural logic
* Tools
* Interactions

---

## Lua

**Lua** is a lightweight scripting language commonly embedded in applications and game engines.

It is useful when an application needs a small scripting system that can operate separately from native engine code.

---

# Systems Programming

## C

**C** is a compiled procedural language with direct access to low-level system concepts.

It is important to:

* Operating systems
* Drivers
* Embedded software
* Language runtimes
* Native libraries

Learning C provides understanding of concepts including:

* Pointers
* Memory
* Stack
* Heap
* Data representation
* Manual allocation
* Native interfaces

---

## C++

**C++** builds on many concepts from C and provides features such as:

* Classes
* Templates
* RAII
* Generic programming
* Standard-library containers

It is widely used in:

* Games
* Engines
* Browsers
* High-performance software
* Desktop applications
* Systems

---

## C#

**C#** is a modern managed language in the .NET ecosystem.

Outside Unity it is widely used for:

* APIs
* Backend systems
* Desktop applications
* Cloud services
* Enterprise software

---

## Rust

**Rust** is a systems language focused strongly on performance and memory safety.

Its ownership model attempts to prevent many memory-management errors during compilation.

Important concepts include:

* Ownership
* Borrowing
* Lifetimes
* Traits
* Pattern matching
* `Option`
* `Result`

---

## Go

**Go** is a compiled language created at Google.

It emphasizes:

* Simplicity
* Networking
* Fast compilation
* Backend services
* Concurrency
* Developer tooling

Important concurrency concepts include:

* Goroutines
* Channels

---

## Java

**Java** is a statically typed language normally executed using the Java Virtual Machine.

It is widely used for:

* Backend services
* Enterprise applications
* Large software systems
* Build tooling
* Android's historical ecosystem

---

# Broader Programming Language Exposure

The following languages represent broader study and experimentation rather than equal everyday proficiency.

## PHP

A server-side programming language strongly associated with web development.

Common ecosystems include:

* WordPress
* Laravel

---

## Ruby

A dynamic object-oriented language known particularly for Ruby on Rails.

---

## Perl

A mature scripting language historically important for:

* Text processing
* Automation
* System administration

---

## Haskell

A purely functional programming language centered around:

* Immutability
* Strong typing
* Higher-order functions
* Lazy evaluation

---

## OCaml

A functional-first language in the ML family.

It provides:

* Type inference
* Pattern matching
* Strong static typing
* Functional programming
* Imperative features

---

## Lisp / Scheme

Lisp is a family of languages based heavily around symbolic expressions and code-as-data.

Scheme is a minimalist Lisp dialect useful for understanding:

* Recursion
* Functional programming
* Interpreters
* Programming-language design

---

## Erlang

Erlang was designed for highly concurrent, distributed, fault-tolerant systems.

Its runtime model strongly influenced technologies such as Elixir.

---

# Data & Scientific Languages

## R

**R** is designed heavily around:

* Statistics
* Data analysis
* Visualization
* Research

---

## MATLAB

**MATLAB** is a numerical computing environment widely used for:

* Engineering
* Mathematics
* Signal processing
* Simulation
* Scientific computing

---

## Julia

**Julia** is designed for high-level numerical and scientific programming while targeting high execution performance.

---

# Mobile Development Exposure

## Swift

**Swift** is Apple's modern programming language.

It is used for Apple platforms including:

* iOS
* macOS
* watchOS
* tvOS

---

## Objective-C

**Objective-C** is an older object-oriented language used extensively in Apple's ecosystem before Swift.

It remains relevant when maintaining existing Apple software.

---

## Kotlin

**Kotlin** is a modern statically typed programming language and a primary language for Android development.

It can also be used for backend and multiplatform development.

---

# Configuration & Markup

## YAML

**YAML** is a human-readable data serialization format.

It is commonly used by:

* GitHub Actions
* Docker Compose
* Deployment systems
* Infrastructure tools
* Application configuration

---

## XML

**XML — Extensible Markup Language** represents structured documents and data.

It is found in:

* Configuration
* APIs
* Document formats
* Enterprise systems
* Feeds
* Older web technologies

---

## TOML

**TOML** is a configuration format designed to map clearly to structured data while remaining human readable.

It is used by ecosystems including Rust's Cargo.

---

# Software Architecture

## Frontend vs Backend

The **frontend** is the part users directly interact with.

The **backend** is responsible for areas such as:

* Business logic
* Authentication
* Authorization
* Database access
* Sensitive secrets
* External integrations

Typical architecture:

`User → frontend → backend/API → database/service`

---

## Authentication vs Authorization

**Authentication** means:

> Who are you?

**Authorization** means:

> What are you permitted to do?

A logged-in user should not automatically have access to every resource.

These should be treated as separate security responsibilities.

---

## Client-Server Architecture

A **client** requests data or actions.

A **server** provides services or resources.

Clients may include:

* Browsers
* Mobile apps
* Desktop applications
* Game clients

Servers may provide:

* APIs
* Databases
* Files
* Authentication
* Application logic

---

# Local-First Software

**Local-first software** prioritizes storing data and running functionality directly on hardware controlled by the user.

Potential advantages include:

* Offline functionality
* User ownership of files
* Privacy
* Reduced dependence on third-party infrastructure
* Faster local communication
* Lower hosting requirements

However:

**local does not automatically mean secure.**

A local application still needs to consider:

* Authentication
* Backups
* File permissions
* Encryption
* Network exposure
* Updates
* Input validation

---

# Privacy by Design

**Privacy by design** means privacy is considered when the architecture is created rather than being added only after development.

Examples include:

* Collecting only necessary information
* Local processing when possible
* Encrypting network traffic
* Limiting data retention
* Protecting secrets
* Providing deletion controls
* Avoiding unnecessary tracking

---

# Input Validation

Any data entering an application should be considered untrusted until validated.

Examples include:

* Form input
* URLs
* API requests
* Query parameters
* File uploads
* Filenames
* Third-party API data

Validation helps prevent both accidental errors and security problems.

---

# Error Handling

Error handling means detecting failures and responding predictably.

Good error handling should:

* Prevent corrupted application state
* Provide useful user feedback
* Create useful developer logs
* Avoid leaking unnecessary internal information

---

# Logging

Logs record events produced by software.

They are useful for diagnosing:

* Crashes
* API failures
* Authentication problems
* Build failures
* Background tasks
* Performance issues
* Network problems

Production logs should avoid containing passwords, tokens, or unnecessary private data.

---

# AI & Local AI Development

## Ollama

**Ollama** is a runtime for running supported AI language models locally.

A local application can communicate with Ollama through a local interface rather than requiring every AI interaction to be sent to a remote API.

Possible advantages include:

* Privacy
* Offline use
* Experimentation
* Local availability

Limitations depend on:

* Available RAM
* GPU/CPU
* Model size
* Quantization
* Context size

---

## Local Language Models

A **local language model** performs inference using hardware controlled by the user.

Benefits may include:

* More control
* Offline operation
* Privacy
* No per-request hosted API dependency

Tradeoffs may include:

* Lower model capability
* RAM requirements
* Storage requirements
* Slower inference
* Smaller context windows

---

## AI-Assisted Development

I use AI as a development accelerator for:

* Architecture exploration
* Coding
* Debugging
* Refactoring
* Documentation
* Learning
* UI iteration
* Test generation

Generated code still requires:

* Understanding
* Review
* Testing
* Security checks
* Integration validation

AI can accelerate engineering, but it does not remove engineering responsibility.

---

# IT Support & Technical Operations

My software-development interests overlap heavily with IT support.

Both require understanding how:

* Applications
* Operating systems
* Hardware
* Networks
* Accounts
* Services
* Users

interact with each other.

Areas I work with include:

* Windows troubleshooting
* Software installation
* Configuration
* Driver troubleshooting
* Peripheral troubleshooting
* Processes
* Services
* Network connectivity
* Browser issues
* Web applications
* User account issues
* Command-line diagnostics
* Development environment setup
* Linux fundamentals
* Reading errors
* Reading logs

My preferred troubleshooting process is:

1. Identify the exact symptom.
2. Reproduce the problem where possible.
3. Determine what changed.
4. Separate possible causes into hardware, OS, network, application, account, or remote-service layers.
5. Collect evidence.
6. Test the lowest-risk explanation first.
7. Change one meaningful thing at a time.
8. Verify the result.
9. Document the solution when useful.

---

# How I Think About Technology

For me, understanding technology means more than remembering syntax or recognizing a logo.

When learning or using a system, I try to answer:

* **What problem does this solve?**
* **Where does it run?**
* **What depends on it?**
* **What data enters it?**
* **What data leaves it?**
* **How does it communicate?**
* **What happens when it fails?**
* **What security boundary does it cross?**
* **Where are secrets stored?**
* **How is it tested?**
* **How is it deployed?**
* **How is it maintained?**
* **What happens to user data?**
* **Could a simpler tool solve the same problem?**

Understanding those questions is more important to me than collecting technology names.

---

# Technology Map

## Typical frontend

`HTML → CSS / Tailwind → JavaScript / TypeScript → React → Next.js / Vite`

## Typical backend

`Client → HTTP / WebSocket → Node.js / Express or Python / FastAPI → validation → application logic → database`

## Data layer

`PostgreSQL | MySQL | SQLite | MongoDB | Firebase`

## Development workflow

`VS Code → Git → GitHub → CI checks → build → deployment`

## Local-first application

`Local frontend → local API/service → local database/files → optional LAN access`

## Security learning

`Linux → networking → packet analysis → service discovery → web request inspection → authorized security testing`

## Game development

`Engine → world/scene → objects/components → scripting → physics/animation → UI → build`

---

# Tools & Environments

<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,python,html,css,tailwind,react,nextjs,nodejs,express,postgres,mysql,sqlite,mongodb,docker,vscode,git,github,cpp,cs,unreal,unity,linux,bash,powershell" alt="Technology icons" />
</p>

---

# GitHub Summary

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=julianomangli&theme=github_dark" height="150" alt="Repositories per language" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=julianomangli&theme=github_dark" height="150" alt="Most committed language" />
</p>

---

# Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=julianomangli&theme=github-compact&hide_border=true" alt="GitHub contribution graph" />
</p>

---

<p align="center">
  <strong>Build. Break down the problem. Understand the system. Improve it.</strong>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=julianomangli&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>
