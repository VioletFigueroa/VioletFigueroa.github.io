# Web Development Portfolio - Application Security Perspective

This document provides a comprehensive overview of how my web development experience from Lighthouse Labs bootcamp directly supports and enhances my application security expertise.

## Executive Summary

My transition from web development to application security is built on a foundation of **hands-on full-stack development experience**. The six projects documented here demonstrate not just coding ability, but **security-conscious development practices** that are essential for AppSec roles. Each project showcases understanding of specific OWASP Top 10 vulnerabilities and their mitigations.

## Project Portfolio Overview

| Project | Primary Security Focus | OWASP Top 10 Coverage | Key Technologies |
|---------|------------------------|----------------------|------------------|
| **TinyApp** | Authentication & Authorization | A07: Identification & Authentication Failures | bcrypt, cookie-session, Express |
| **Tweeter** | XSS Prevention | A03: Injection (XSS) | HTML escaping, input validation, jQuery |
| **LightBnB** | SQL Injection Prevention | A03: Injection (SQLi) | PostgreSQL, parameterized queries |
| **Interview Scheduler** | Client-Side Security | A04: Insecure Design | React hooks, WebSocket security, error handling |
| **Scheduler API** | API Security | A01: Broken Access Control, A05: Security Misconfiguration | Helmet, CORS, environment variables |
| **Lotide** | Secure Development Practices | A06: Vulnerable Components | TDD, input validation, npm security |

## Security Skills Demonstrated Across Projects

### 1. **OWASP Top 10 Understanding**

Each project addresses specific vulnerabilities from the OWASP Top 10:

- **A01: Broken Access Control** - TinyApp's authorization checks ensure users can only access their own URLs
- **A03: Injection** - LightBnB uses parameterized queries; Tweeter implements XSS escaping
- **A05: Security Misconfiguration** - Scheduler API uses Helmet headers and proper CORS configuration
- **A07: Identification & Authentication Failures** - TinyApp implements bcrypt password hashing and secure sessions

### 2. **Defense in Depth**

Multiple layers of security demonstrated:

```
Client Side (Tweeter, Interview Scheduler)
├── Input validation (character limits, format checks)
├── XSS escaping (HTML entity encoding)
└── Error handling (user-friendly messages)

Server Side (TinyApp, LightBnB, Scheduler API)
├── Authentication (bcrypt, session management)
├── Authorization (resource ownership checks)
├── Input validation (server-side re-validation)
├── SQL injection prevention (parameterized queries)
└── Security headers (Helmet middleware)

Database (LightBnB)
├── Constraints (foreign keys, NOT NULL, CHECK)
├── Connection pooling (resource management)
└── Least privilege (limited database user permissions)
```

### 3. **Secure Development Lifecycle**

- **Test-Driven Development** (Lotide, Interview Scheduler) - Security testing from the start
- **Code Review Practices** - Clean, documented code facilitates security review
- **Version Control** - Git tracking enables security regression analysis
- **Dependency Management** - Conscious choice of security-focused packages
- **Environment-Based Configuration** - Secrets management best practices

### 4. **Threat Modeling Capability**

Each project demonstrates understanding of specific threat vectors:

| Project | Threats Identified | Mitigations Implemented |
|---------|-------------------|-------------------------|
| TinyApp | Session hijacking, password theft, unauthorized access | Signed cookies, bcrypt hashing, authorization checks |
| Tweeter | XSS attacks, CSRF | HTML escaping, safe DOM manipulation |
| LightBnB | SQL injection, data exposure | Parameterized queries, error sanitization |
| Scheduler API | CORS attacks, header exploitation, secrets exposure | CORS policy, Helmet headers, dotenv |

### 5. **Security Testing Experience**

- **Unit Testing** - Lotide's comprehensive test suite validates edge cases
- **Integration Testing** - Interview Scheduler tests API interactions
- **Error State Testing** - Scheduler API's error mode validates client resilience
- **Manual Security Testing** - Testing authorization bypasses, injection attempts

## Application Security Career Value

### Code Review Skills

**What I bring:**
- Ability to read and understand full-stack codebases (React, Node.js, Express)
- Experience identifying security anti-patterns (string concatenation in SQL, unsafe HTML rendering)
- Understanding of secure coding patterns (parameterized queries, input validation, error handling)

**Projects demonstrating this:**
- Reviewed and refactored Lotide functions for edge case handling
- Implemented XSS prevention in Tweeter through code analysis
- Applied security best practices in TinyApp authentication flow

### Security Testing & Validation

**What I bring:**
- Hands-on testing of authentication and authorization flows
- Experience testing for injection vulnerabilities (XSS, SQLi)
- Understanding of both positive and negative test cases

**Projects demonstrating this:**
- TinyApp: Manual testing of authorization bypasses
- Tweeter: Testing XSS payload escaping
- LightBnB: Validating parameterized query protection

### Developer Security Champion

**What I bring:**
- Ability to explain security concepts to developers in their language
- Experience implementing security controls in real applications
- Understanding of developer pain points and security friction

**Projects demonstrating this:**
- Documentation explaining security decisions and trade-offs
- Code examples showing secure vs. insecure patterns
- Practical security implementations that don't break functionality

### Security Architecture & Design

**What I bring:**
- Experience designing secure APIs (Scheduler API)
- Understanding of client-server security boundaries (Interview Scheduler + API)
- Knowledge of security control placement across application layers

**Projects demonstrating this:**
- Three-tier architecture in LightBnB (client, server, database)
- Separation of concerns in modular Lotide library
- WebSocket security integration in Scheduler API

## Technical Proficiency for AppSec

### Programming Languages
- **JavaScript/Node.js** - Primary language across all projects
- **SQL** - PostgreSQL queries and schema design
- **HTML/CSS** - Client-side security context

### Security Technologies
- **Authentication:** bcrypt, cookie-session, session management
- **Input Validation:** Server-side and client-side validation patterns
- **Injection Prevention:** Parameterized queries, HTML escaping
- **API Security:** Helmet, CORS, environment variables
- **Testing:** Jest, Mocha, Chai, React Testing Library

### Development Tools
- **Git/GitHub** - Version control and collaboration
- **npm** - Package management and dependency security
- **PostgreSQL** - Database security and administration
- **Express.js** - Middleware and security patterns
- **React** - Client-side security considerations

## Unique Value Proposition

### Developer Background in AppSec Context

Most security professionals come from either:
1. **Pure security background** - Strong security knowledge, limited development experience
2. **Senior developer background** - Deep coding skills, learning security later

I bring a **unique middle ground:**
- **Formal development training** - Not self-taught, but structured bootcamp education
- **Recent development experience** - Current knowledge of modern frameworks and practices
- **Security-first mindset** - Developed security consciousness during coding projects
- **Cross-functional capability** - Can code production features AND secure them

### Real-World Application

These aren't theoretical projects - they're functional applications demonstrating:
- **Production-ready patterns** - Error handling, logging, testing, documentation
- **Security integration** - Security controls built in, not bolted on
- **Practical trade-offs** - Understanding when to prioritize security vs. usability
- **Full-stack perspective** - Security considerations across all application layers

## Interview Talking Points

### "Tell me about your development experience"

*"I completed a full-stack web development bootcamp where I built six major projects covering authentication, XSS prevention, SQL injection mitigation, API security, and secure coding practices. What makes my experience unique is that I approached every project with a security mindset - for example, in my TinyApp project, I implemented bcrypt password hashing and cookie-based session management not because it was required, but because I understood the security implications of authentication. This development background gives me the practical experience to work effectively with engineering teams and review code from a developer's perspective."*

### "How do you handle security vs. usability trade-offs?"

*"In my Interview Scheduler project, I had to balance comprehensive error messaging with information disclosure risks. I implemented client-side error messages that were user-friendly but generic ('Unable to save appointment'), while logging detailed errors server-side for debugging. This approach maintains usability without exposing stack traces or system internals to potential attackers. I've learned that the best security controls are transparent to users doing the right thing, but block malicious activity effectively."*

### "Describe your experience with the OWASP Top 10"

*"I've implemented mitigations for several OWASP Top 10 vulnerabilities across my projects. For injection attacks, I used parameterized queries in my LightBnB database project and implemented HTML escaping in my Tweeter application to prevent XSS. For broken authentication, my TinyApp project uses bcrypt for password hashing with proper salt rounds and secure session management. In my Scheduler API, I addressed security misconfiguration by implementing Helmet security headers and proper CORS policies. Each project gave me hands-on experience not just understanding these vulnerabilities theoretically, but actually preventing them in code."*

## Continuous Learning & Growth

**Current Focus:**
- Expanding cybersecurity expertise through digital forensics and incident response projects
- Combining development skills with security knowledge for AppSec roles
- Studying security testing tools (SAST/DAST) to complement manual code review skills

**Future Direction:**
- Integrate security testing tools into development workflows
- Contribute to open-source security projects
- Develop security training materials for developers

## Conclusion

My web development background isn't a detour from application security - **it's the foundation that makes me effective in AppSec roles**. I understand how developers think, how applications are built, and where security vulnerabilities are introduced. I can review code, test applications, and work with engineering teams because I've been in their shoes. Combined with my cybersecurity training and projects, this creates a comprehensive skill set uniquely suited for modern application security roles where collaboration with development teams is essential.

---

**Author:** Violet Figueroa  
**GitHub:** [github.com/VioletFigueroa](https://github.com/VioletFigueroa)  
**Career Focus:** Application Security | Secure Software Development | Security Engineering
