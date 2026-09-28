<div align="center">

# James Brian Ndung'u

### Software Engineer · Backend · Systems

I build software to understand how systems actually work.

<br>

<a href="https://github.com/James-oss796">
  <img src="https://img.shields.io/badge/GitHub-James--oss796-111827?style=flat-square&logo=github&logoColor=white" alt="GitHub">
</a>
&nbsp;
<a href="https://gwen-books.vercel.app">
  <img src="https://img.shields.io/badge/GwenBooks-Live-111827?style=flat-square" alt="GwenBooks">
</a>
&nbsp;
<a href="mailto:jamesbriandungu@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-111827?style=flat-square&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=James-oss796&style=flat-square&color=111827" alt="Profile views">

</div>

---

## A little about me

I'm a software engineer focused mainly on **backend development and systems**.

Most of my work currently revolves around:

* Java and Spring Boot
* REST APIs and authentication
* PostgreSQL and MySQL
* React and Next.js
* Docker and Linux
* Blockchain and smart contracts
* Building and deploying applications

I learn by building things, breaking them, figuring out why they broke, and rebuilding them properly.

I'm particularly interested in what happens **between the lines of code**:

```text
request
   ↓
HTTP
   ↓
API
   ↓
business logic
   ↓
database
   ↓
response

and eventually...

code
   ↓
container
   ↓
server
   ↓
network
   ↓
user
```

That part of software interests me more than simply making a screen look good.

---

## What I'm building

### GwenBooks

A multi-source digital book discovery and reading platform.

**Live:** https://gwen-books.vercel.app

GwenBooks started as a project for learning full-stack development and gradually became a proper application involving external APIs, authentication, databases, deployment and a real user interface.

```text
                         GwenBooks

                           User
                            │
                            ▼
                    ┌──────────────┐
                    │   Next.js    │
                    │   Frontend   │
                    └──────┬───────┘
                           │
              ┌────────────┼────────────┐
              ▼            ▼            ▼
        Open Library   Gutenberg   Internet Archive
              │            │            │
              └────────────┼────────────┘
                           ▼
                    Application Logic
                           │
                           ▼
                    Neon PostgreSQL
```

**Built with**

`Next.js` `TypeScript` `React` `Tailwind CSS` `Drizzle` `PostgreSQL` `REST APIs` `Vercel`

---

## Other things I've built

| Project               | Problem                                           |
| --------------------- | ------------------------------------------------- |
| **PesaChain**         | Blockchain-based microfinance and loan management |
| **AfyaFlow**          | Hospital queue and appointment management         |
| **Attendance System** | Time and location-based student attendance        |
| **KodiTrack**         | Rental and tenant management                      |
| **GwenBooks**         | Multi-source book discovery and reading           |

I try to make projects solve an actual problem instead of creating another `todo-app-final-final-2`.

---

## PesaChain

One of my current larger projects.

The idea is to combine a conventional backend with blockchain where blockchain actually adds value.

```text
                     Borrower
                        │
                        ▼
                 React / Vite
                        │
                REST API / JWT
                        │
                        ▼
                Spring Boot API
                   /         \
                  /           \
                 ▼             ▼
          PostgreSQL       Smart Contract
                              │
                              ▼
                           Ethereum
```

The interesting part for me isn't simply writing Solidity.

It's understanding **where blockchain belongs in a normal software architecture** and where it doesn't.

**Stack**

`Java` `Spring Boot` `PostgreSQL` `React` `Solidity` `Ethereum` `Hardhat` `Ganache` `MetaMask` `Web3.js`

---

## The stack

I don't consider every technology below an equal level of expertise. Some are things I use regularly; others are technologies I'm actively learning.

### Languages

<img src="https://skillicons.dev/icons?i=java,js,ts,python,c,bash,html,css" />

`SQL` · `Solidity`

### Backend

<img src="https://skillicons.dev/icons?i=spring" />

`Spring Boot` · `Spring Security` · `Spring Data JPA` · `Hibernate`
`REST APIs` · `JWT` · `Maven` · `JUnit`

### Frontend

<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind" />

`React` · `Next.js` · `Vite` · `Tailwind CSS` · `shadcn/ui`

### Databases

<img src="https://skillicons.dev/icons?i=postgres,mysql" />

`PostgreSQL` · `MySQL` · `Neon` · `Drizzle ORM` · `Hibernate` · `pgAdmin`

### Development & Infrastructure

<img src="https://skillicons.dev/icons?i=linux,docker,git,github,vscode,idea" />

`Linux` · `Docker` · `Docker Compose` · `Git` · `GitHub`
`VS Code` · `IntelliJ IDEA` · `Postman` · `Docker Desktop`

### Web3

<img src="https://skillicons.dev/icons?i=solidity,ethereum" />

`Solidity` · `Ethereum` · `Hardhat` · `Ganache`
`MetaMask` · `Web3.js` · `OpenZeppelin` · `Remix`

---

## How I currently think about software

I'm gradually moving from:

```text
"How do I make this feature work?"
```

towards:

```text
"How does the whole system behave?"
```

That means learning to think about:

```text
             ┌───────────────┐
             │    Client     │
             └───────┬───────┘
                     │
                  HTTP
                     │
                     ▼
             ┌───────────────┐
             │      API      │
             └───────┬───────┘
                     │
                     ▼
             ┌───────────────┐
             │    Backend    │
             └───────┬───────┘
                     │
             ┌───────┴────────┐
             ▼                ▼
        ┌─────────┐     ┌───────────┐
        │ Database│     │ External  │
        │         │     │ Services  │
        └─────────┘     └───────────┘
             │
             ▼
        Docker / Linux
             │
             ▼
        Deployment
```

The goal is to understand each boundary:

**HTTP → API → application → database → infrastructure**

rather than treating the framework as a black box.

---

## Currently working on

```text
Backend Engineering
        │
        ├── Java
        ├── Spring Boot
        ├── Spring Security
        ├── REST APIs
        ├── PostgreSQL
        └── Testing

Infrastructure
        │
        ├── Linux
        ├── Docker
        └── Docker Compose

Web3
        │
        ├── Solidity
        ├── Smart Contracts
        ├── Ethereum
        └── DApp integration
```

The longer-term direction is toward **cloud and DevOps**, built on top of a strong software engineering foundation.

---

## Things I want to get better at

Not everything has to be another framework.

The areas I'm deliberately working toward are:

```text
Software Engineering
        ↓
Backend Systems
        ↓
Linux + Networking
        ↓
Containers
        ↓
Cloud Infrastructure
        ↓
CI/CD
        ↓
Distributed Systems
```

The aim is to understand the entire path from:

```text
        "someone clicked a button"
                    ↓
              HTTP request
                    ↓
                backend
                    ↓
                database
                    ↓
              infrastructure
                    ↓
              actual server
```

---

## Some engineering questions I keep coming back to

<details>
<summary><b>What happens when the database goes down?</b></summary>

The application shouldn't simply become a mystery.

I'm interested in understanding connection pools, transactions, retries, failure handling, logging and how the application behaves when dependencies are unavailable.

</details>

<details>
<summary><b>What actually happens when an API receives a request?</b></summary>

From DNS and TCP/HTTP through routing, authentication, controllers, services, database queries and the response sent back to the client.

</details>

<details>
<summary><b>Why Docker?</b></summary>

Not just because "Docker is used in industry."

I want to understand isolation, images, containers, networking, volumes, environment configuration and why containerisation changes how applications are developed and deployed.

</details>

<details>
<summary><b>Where does blockchain actually help?</b></summary>

A blockchain shouldn't be added to an application just because it sounds impressive.

I'm interested in understanding the cases where decentralised state, verifiability and smart contracts provide something a conventional database cannot provide as effectively.

</details>

---

## GitHub activity

I want this profile to eventually tell a story through the work itself.

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=James-oss796&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" height="165">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=James-oss796&layout=compact&hide_border=true&theme=transparent" height="165">

</div>

<br>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=James-oss796&hide_border=true&theme=transparent">

</div>

---

## Outside the code

Software isn't the only thing I work on.

I'm interested in technology broadly, especially the point where **software, networks and real-world systems** meet.

I also work on projects involving design, documentation and community activities. Figma and Canva occasionally make appearances in a repository that was supposed to be "backend only."

---

## A small rule I try to follow

```text
Don't just copy the solution.

Understand why it works.

Then build it again without the tutorial.
```

---

<div align="center">

### James Brian Ndung'u

`Software Engineer` · `Backend` · `Systems` · `Cloud`

<br>

<a href="mailto:jamesbriandungu@gmail.com">Email</a>
  ·   <a href="https://github.com/James-oss796">GitHub</a>
  ·   <a href="https://gwen-books.vercel.app">GwenBooks</a>

<br><br>

<sub>Still building.</sub>

</div>
