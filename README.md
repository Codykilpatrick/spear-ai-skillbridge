# 3-Month Software Engineering Training Pipeline for Spear AI

## Overview

| | |
|---|---|
| **Total Duration** | 3 months (~14 weeks including Week 0) |
| **Budget** | 1 Udemy personal plan ($14.99/month) |
| **Target Roles** | Full Stack Engineer, Infrastructure Engineer, Modernization Engineer |

---

## Why Each Technology Matters at Spear

| Technology | Why It Matters | Where It's Used |
|------------|----------------|-----------------|
| **React/TypeScript** | Internal tooling and client-facing dashboards | Website, Horizon |
| **Node.js** | Backend services and build tooling | Various microservices |
| **Python** | Data processing pipelines, ML integration, scripting | ML applications, Horizon data pipeline |
| **PostgreSQL** | Primary database for structured data | Horizon, Forerunner |
| **Docker/K8s** | Everything runs containerized in deployment environments | Modernization, cloud efforts, Horizon deployments |
| **Rust** | Modernization target for performance-critical legacy C code | Replanner, Modernization efforts, Data processing |

---

## Week 0: Environment Setup & Git Fundamentals

**Duration:** 1 week (before Month 1 begins)  
**Purpose:** Get all candidates on the same page with tooling, accounts, and version control basics before diving into coursework.

### Day 1-2: Account Setup & Installations

#### Tasks
- [ ] Create a GitHub account (if you don't have one)
- [ ] Install Git on your machine
- [ ] Install VS Code
- [ ] Configure Git with your name and email
- [ ] Set up SSH keys for GitHub authentication

#### Installation Resources

**Git Installation:**
- **Windows:** Download [Git for Windows](https://git-scm.com/download/win) (includes Git Bash)
- **Mac:** Install via Homebrew (`brew install git`) or download from [git-scm.com](https://git-scm.com/download/mac)
- **Linux:** `sudo apt install git` (Ubuntu/Debian) or `sudo dnf install git` (Fedora)

**VS Code Installation:**
- Download from [code.visualstudio.com](https://code.visualstudio.com/)

**SSH Key Setup:**
- [GitHub Docs: Generating SSH Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

### Day 2-4: Git Fundamentals

#### Primary Video Tutorial

**Git It? How to use Git and Github** by Fireship  
- Link: https://www.youtube.com/watch?v=HkdAHXoRtos  
- Length: ~12 minutes  
- Covers: What Git is, initializing repos, .gitignore, staging, commits, pushing, pull requests

*Fast-paced overview - watch first to get the big picture.*

#### Deep Dive Tutorial

**Git and GitHub for Beginners - Crash Course** by freeCodeCamp  
- Link: https://www.youtube.com/watch?v=RGOj5yH7evk  
- Length: ~1 hour  
- Covers: Git setup, commands, GitHub workflows, branching, merging, forking

#### Interactive Practice (Required)

**Learn Git Branching**  
- Link: https://learngitbranching.js.org/  
- Length: 2-4 hours  
- Complete: "Main" levels 1-4 (Introduction Sequence) and "Remote" levels 1-8

*Browser-based sandbox that visualizes Git operations. Highly recommended.*

### Day 4-5: VS Code Fundamentals

#### Primary Tutorial

**VS Code Official Intro Videos**  
- Link: https://code.visualstudio.com/docs/getstarted/introvideos  
- Length: ~30 minutes total  
- Covers: Setup, editing, productivity tips, themes, extensions, debugging, Git integration

#### Supplemental Video

**VSCode Tutorial For Beginners** by Tech With Tim  
- Link: https://www.youtube.com/watch?v=VqCgcpAypFQ  
- Length: ~30 minutes  
- Covers: Project setup, file explorer, terminal, extensions, settings, Git tools

#### Essential Extensions to Install
- **ESLint** - JavaScript/TypeScript linting
- **Prettier** - Code formatting
- **GitLens** - Enhanced Git capabilities
- **Thunder Client** - API testing
- **Error Lens** - Inline error highlighting

### Day 5-7: Practice Project

#### Mini-Project: "Hello Spear"

Create your first repository and practice the Git workflow:

1. Create a new repo on GitHub called `hello-spear`
2. Clone it to your local machine
3. Create a simple `README.md` with:
   - Your name
   - Why you're joining the SkillBridge program
   - One thing you're excited to learn
4. Stage, commit, and push your changes
5. Create a new branch called `add-goals`
6. Add a section listing 3 learning goals for the program
7. Commit and push the branch
8. Create a Pull Request on GitHub
9. Merge the PR into main
10. Pull the changes back to your local main branch

**Deliverable:** Share the GitHub repo - Link with your mentor

### Week 0 Checklist

- [ ] GitHub account created
- [ ] Git installed and configured
- [ ] VS Code installed with essential extensions
- [ ] SSH keys set up for GitHub
- [ ] Completed Fireship Git video
- [ ] Completed freeCodeCamp Git crash course
- [ ] Completed Learn Git Branching (Intro + Remote basics)
- [ ] Watched VS Code intro videos
- [ ] "Hello Spear" practice repo completed and shared

---

## Month 1: Full-Stack Foundations (Weeks 1-5)

**Focus:** Backend, Frontend, and Database fundamentals  
**Duration:** 5 weeks

### Core Technologies Covered

- **Backend:** Node.js, Express, REST APIs, authentication
- **Frontend:** React, TypeScript, Tailwind CSS
- **Database:** PostgreSQL, SQL fundamentals
- **Languages:** JavaScript, Python
- **Tools:** Git, VS Code, npm/yarn

### Week 1-2: Backend Development

#### Primary Course

**NodeJS - The Complete Guide (MVC, REST APIs, GraphQL, Deno)**  
*Instructor: Maximilian Schwarzmüller (Academind)*

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | 40+ hours |
| **Last Updated** | November 2025 |
| **Rating** | 4.6 stars (53,000+ reviews) |

**Coverage:**
- Node.js fundamentals and how it works under the hood
- Express.js framework and MVC architecture
- REST API design and development
- Authentication with sessions, cookies, and JWT
- File uploads and sending emails
- SQL and NoSQL databases
- Testing and deployment
- Introduction to GraphQL and Deno

**Projects:** Build a complete online shop with authentication, payments, and REST API

### Week 2-3: Frontend Development

#### Primary Course

**The Complete React Developer Course**

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | 40+ hours (actual ~70 hours with practice) |

**Coverage:**
- React fundamentals and component architecture
- TypeScript integration
- State management with hooks
- Building reusable components
- Routing and navigation

**Projects:** Build 3 React applications

### Week 4: Python & Database

#### Python Course

**The Complete Python Bootcamp**
- Link: https://www.udemy.com/course/complete-python-bootcamp/ 

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | 22+ hours |

**Coverage:**
- Python fundamentals
- Type hints and mypy
- Data structures and algorithms
- Object-oriented programming

**Projects:** Command-line tools, scripting exercises

#### Database Training

**PostgreSQL Tutorial** (Free)

| | |
|---|---|
| **Duration** | 15+ hours |

**Instructions:**

1. **Install PostgreSQL on macOS**
   - Follow the installation guide at: https://neon.com/postgresql/postgresql-getting-started/install-postgresql-macos
   - This walks you through downloading the installer, running the setup wizard, and loading the sample `dvdrental` database using pgAdmin

2. **Complete Sections 1 & 2 of the PostgreSQL Tutorial**
   - Tutorial home: https://neon.com/postgresql/tutorial
   - **Section 1 – Querying Data:**
   - **Section 2 – Filtering Data:**

3. **Complete the LabEx PostgreSQL Skill Tree**
   - https://labex.io/skilltrees/postgresql
   - This is a hands-on, interactive learning path covering SQL fundamentals through advanced topics.

**Coverage:**
- SQL basics (SELECT, INSERT, UPDATE, DELETE)
- Joins and relationships
- Advanced queries and subqueries
- Indexing and performance optimization

### Week 5: Portfolio Project

#### Project: Personal Portfolio Website

**Technologies:** React + TypeScript + Tailwind CSS

**Requirements:**
- Responsive design (desktop, tablet, mobile)
- TypeScript throughout (properly typed components)
- Tailwind CSS for styling (no custom CSS files)
- Hosted and publicly accessible

**Core Sections:**
- Hero/introduction
- Skills showcase (technologies learned)
- Projects gallery (will grow each month)
- Contact form with validation

**Deliverable:** Share hosted URL with mentor for review

*Note: Portfolio doesn't need to be fully polished - the goal is something functional and hosted that we can review together. You'll continue improving it throughout the program.*

### Month 1 Milestones

- [ ] Complete Node.js course and build REST API project
- [ ] Complete React course and build component-based applications
- [ ] Demonstrate SQL proficiency with PostgreSQL
- [ ] Complete Python fundamentals
- [ ] Deploy portfolio website (hosted and accessible)

### Month 1 Time Estimate

| Content | Hours |
|---------|-------|
| Node.js course | ~40 |
| React course | ~70 |
| Tailwind supplement | ~4 |
| Python course | ~22 |
| PostgreSQL tutorial | ~15 |
| Portfolio project | ~15-20 |
| **Total** | **~165-170 hours** |

*At ~35 hours/week, this fits comfortably in 5 weeks.*

---

## Month 2: Infrastructure & DevOps (Weeks 6-9)

**Focus:** Cloud infrastructure, containerization, and CI/CD  
**Duration:** 4 weeks

### Core Technologies Covered

- **Cloud:** AWS (EC2, S3, RDS, Lambda)
- **Containerization:** Docker, Docker Compose
- **Infrastructure as Code:** Terraform (transferable to Pulumi)
- **CI/CD:** GitHub Actions
- **Monitoring:** Basic logging and metrics

### Week 6-7: Docker & Containerization

#### Primary Course

**Docker Mastery: with Kubernetes + Swarm**

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | 19+ hours |

**Coverage:**
- Docker fundamentals
- Docker Compose
- Container orchestration

**Projects:** Containerize previous month's applications

### Week 8-9: AWS & Infrastructure

#### Primary Course

**AWS Certified Solutions Architect Associate**

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | 27+ hours |

**Coverage:**
- AWS services
- Cloud architecture
- Security

**Projects:** Deploy applications to AWS

#### Supplement

**Terraform Tutorial** (Free - HashiCorp Learn)

| | |
|---|---|
| **Duration** | 10+ hours |

**Coverage:** Infrastructure as Code principles (easily transferable to Pulumi)

### Month 2 Projects

1. **Dockerized Application Stack** (Frontend + Backend + Database)
2. **AWS Deployment** (EC2, RDS, S3 integration)
3. **CI/CD Pipeline** (GitHub Actions for automated testing and deployment)
4. **Infrastructure as Code** (Terraform scripts for AWS resources)

### Month 2 Milestones

- [ ] Containerize applications with Docker
- [ ] Deploy to AWS cloud infrastructure
- [ ] Implement CI/CD pipeline
- [ ] Create infrastructure as code

---

## Month 3: Systems Programming & Advanced Topics (Weeks 10-13)

**Focus:** Low-level programming, performance optimization, and specialized skills  
**Duration:** 4 weeks

### Core Technologies Covered

- **Systems Programming:** Rust, memory management
- **Advanced Python:** Performance optimization, testing
- **Security:** Authentication, authorization, secure coding
- **Testing:** Unit testing, integration testing, performance testing

### Week 10-11: Systems Programming

#### Primary Course

**The Complete Rust Programming Course**

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | 17.5+ hours |

**Coverage:**
- Rust fundamentals
- Ownership and memory safety
- Concurrency
- Data structures

**Projects:** Build CLI tools, system utilities, concurrent applications

**Features:** Hands-on challenges, practical exercises, comprehensive coverage

#### Secondary Course

**Rust: The Complete Developer's Guide**  
*Instructor: Stephen Grider*

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | Comprehensive |

**Coverage:**
- Advanced Rust concepts
- Lifetimes, traits, generics
- Best practices

**Projects:** Progressive complexity projects, real-world applications

#### Supplement

**The Rust Programming Language Book** (Free - Official Rust Documentation)

| | |
|---|---|
| **Duration** | Self-paced |

**Coverage:** Comprehensive Rust reference and examples

### Week 12-13: Testing & Advanced Topics

#### Primary Course

**Python Unit Testing Fundamentals (using unittest & pytest)**

| | |
|---|---|
| **Cost** | Included in personal plan |
| **Duration** | Comprehensive |

**Coverage:**
- Unit testing fundamentals
- Test cases and test suites
- Fixtures and mocking

**Projects:** Hands-on examples with practical testing scenarios

#### Free Resources

- LangChain Tutorial (Free)
- Linux Command Line Tutorial (Free)
- Git Advanced Tutorial (Free)

### Month 3 Projects

1. **Rust CLI System Utility** (File processing, memory safety, concurrency)
2. **Performance-Optimized Python Application** (With comprehensive testing)

### Month 3 Milestones

- [ ] Write efficient Rust programs with memory safety
- [ ] Implement comprehensive testing strategies
- [ ] Demonstrate security best practices
- [ ] Complete advanced projects

---

## Learning Support Structure

### Tools & Environment

- **IDE:** VS Code
- **Version Control:** Git/GitHub
- **Communication:** Slack for collaboration
- **Project Management:** Linear
- **Documentation:** Notion



---

## Monthly Project Guidelines

### Month 1 Projects

#### 1. Personal Portfolio Website (Required)

**Technologies:** React + TypeScript + Tailwind CSS  
**Timeline:** 2-3 weeks  
**Purpose:** Demonstrate frontend skills and serve as a showcase for all future projects

**Requirements:**
- **Responsive Design:** Must work on desktop, tablet, and mobile
- **TypeScript:** All components must be properly typed
- **Tailwind CSS:** Use utility-first CSS approach, no custom CSS files
- **React Best Practices:** Functional components, hooks, proper state management
- **Accessibility:** ARIA labels, semantic HTML, keyboard navigation

**Core Features:**
- Hero section with professional introduction
- Skills showcase (technologies learned)
- Projects gallery (will grow each month)
- Contact form with validation
- Dark/light mode toggle
- Smooth scrolling navigation

### Month 2 Projects

#### 1. Dockerized Full-Stack Application (Required)

**Technologies:** Docker + Docker Compose + Previous Month's Projects  
**Timeline:** 2-3 weeks  
**Purpose:** Demonstrate containerization and orchestration skills

**Requirements:**
- **Multi-Container Setup:** Separate containers for frontend, backend, and database
- **Docker Compose:** Orchestrate all services with proper networking
- **Environment Configuration:** Use environment variables for configuration
- **Volume Management:** Persistent data storage for database
- **Development vs Production:** Different configurations for each environment

**Core Features:**
- Frontend container (React app with Nginx)
- Backend container (Node.js API)
- Database container (PostgreSQL)
- Redis cache container (optional)
- Health checks for all services
- Automated database migrations

**Deliverables:**
- Multi-stage Dockerfiles for each service
- Docker Compose files for dev and prod
- Environment variable templates
- Setup and deployment documentation
- Container orchestration demonstration

#### 2. AWS Cloud Deployment (Optional)

**Technologies:** AWS (EC2, RDS, S3) + Previous Projects  
**Timeline:** 1-2 weeks  
**Purpose:** Demonstrate cloud deployment and infrastructure management

**Requirements:**
- **EC2 Deployment:** Host application on EC2 instances
- **RDS Integration:** Managed database service
- **S3 Storage:** Static assets and file uploads
- **Security Groups:** Proper network security configuration
- **Load Balancing:** Application Load Balancer (if multiple instances)

**Core Features:**
- Production-ready application deployment
- SSL certificate configuration
- Database backups and monitoring
- Static asset delivery via S3
- Basic monitoring and logging
- Auto-scaling groups (optional)

### Month 3 Projects

#### 1. Rust CLI System Utility (Required)

**Technologies:** Rust + Cargo + System APIs  
**Timeline:** 2-3 weeks  
**Purpose:** Demonstrate systems programming and Rust proficiency

**Requirements:**
- **Command Line Interface:** Proper argument parsing and help text
- **File System Operations:** Read, write, and manipulate files efficiently
- **Concurrency:** Use Rust's async/await or threading for performance
- **Error Handling:** Comprehensive error handling with user-friendly messages
- **Memory Safety:** Demonstrate Rust's ownership and borrowing concepts

**Project Options (Choose One):**
- **Log Analyzer:** Parse and analyze server logs with statistics and filtering
- **File Synchronizer:** Sync files between directories with change detection
- **System Monitor:** Real-time monitoring of CPU, memory, and disk usage
- **Backup Utility:** Incremental backup system with compression and encryption

**Core Features:**
- Multi-threaded/async processing
- Progress bars and real-time feedback
- Configuration file support
- Cross-platform compatibility
- Comprehensive testing suite
- Performance benchmarks

#### 2. Performance-Optimized Python Application (Required)

**Technologies:** Python + mypy + pytest + Performance Tools  
**Timeline:** 2-3 weeks  
**Purpose:** Demonstrate advanced Python skills and performance optimization

**Requirements:**
- **Type Annotations:** Full mypy compliance with strict settings
- **Testing Suite:** Comprehensive unit and integration tests
- **Performance Profiling:** Use profiling tools to identify bottlenecks
- **Optimization:** Implement caching, algorithmic improvements, or async processing
- **Monitoring:** Basic metrics collection and performance tracking

**Project Options (Choose One):**
- **Data Processing Pipeline:** ETL pipeline with large dataset processing
- **Web Scraper:** High-performance concurrent web scraping system
- **API Gateway:** Request routing and rate limiting service
- **Machine Learning Service:** Model serving with optimization and caching

**Core Features:**
- Async/await for I/O operations
- Caching layer (Redis or in-memory)
- Database connection pooling
- Batch processing capabilities
- Comprehensive logging
- Performance metrics dashboard

**Testing Requirements:**
- Unit tests with 100% coverage
- Integration tests for key workflows
- Performance benchmarks
- Load testing scenarios
- Property-based testing (optional)

---

## General Guidelines for All Projects

### Documentation Standards

- **README.md:** Setup instructions, usage examples, architecture overview
- **Code Comments:** Clear, concise comments explaining complex logic

### Code Quality Standards

- **Version Control:** Clean commit history with descriptive messages
- **Code Review:** Self-review checklist before submission
- **Linting:** Use appropriate linters for each language
- **Formatting:** Consistent code formatting across all files

### Submission Requirements

- **Live Demo:** Deployed application with public URL
- **Source Code:** Clean, well-organized GitHub repository
- **Documentation:** Complete setup and usage instructions
- **Reflection:** Brief writeup on challenges and learnings

---

## SkillBridge-Specific Notes

### Time Expectations

- Plan for ~35 hours/week on coursework and projects, this is flexible as needed.

### Networking

- First 2-3 networking intros will be facilitated
- After that, network independently (every other week)

### Check-ins

- Weekly async updates in Slack
- weekly syncs
- Monthly formal reviews
