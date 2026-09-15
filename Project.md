# 📚 Full Stack Development — Case Study Exam

**Instructor:** Sadeed  
**Course:** Introduction to Full Stack Development  
**Total Marks:** 100  

**Instructions:**

- Answer all questions.
- Clearly justify all technical decisions.
- Diagrams are encouraged where required.
- Focus on architecture thinking, stack selection, databases, APIs, scalability, and business requirements.
- Assume you are part of a software engineering team proposing technical solutions.

---

# Case Study 1 — Car Dealership Inventory Platform

## Scenario

A company similar to AutoTrader wants to build a platform where:

- Car dealerships upload inventory daily
- Some dealerships upload:
  - CSV files
  - Excel files
- The public can:
  - Search vehicles
  - Filter by price/year/location
- The system updates inventory every few hours
- The platform stores sold vehicle history
- Traffic increases heavily during weekends

---

## Questions

### Q1.1 — System Analysis (10 Marks)

Identify whether this system is:

- Realtime
- Near realtime
- Batch processing

Explain your answer.

---

### Q1.2 — Architecture Thinking (10 Marks)

Explain why CSV or Excel bulk uploads may make sense for this business model.

Why might APIs not be available for all dealerships?

---

### Q1.3 — Stack Selection (10 Marks)

Choose ONE stack below and justify your answer:

- MERN
- MEAN
- .NET
- Django
- Spring Boot

Your answer must include:

- frontend choice
- backend choice
- scalability considerations
- business reasoning

---

### Q1.4 — Database Design (10 Marks)

Would you use:

- SQL
- NoSQL
- Hybrid approach

Explain your reasoning.

Identify examples of:

- structured data
- semi-structured data

---

### Q1.5 — Architecture Diagram (10 Marks)

Draw a high-level architecture diagram showing:

- client
- web server
- backend/API
- upload service
- database

Bonus:
Add caching to your design.

---

# Case Study 2 — Food Delivery Platform

## Scenario

A startup wants to build a food delivery system similar to Uber Eats.

Features include:

- Live order tracking
- Driver assignment
- Push notifications
- GPS updates
- Online payments
- Mobile applications
- Restaurant dashboards

---

## Questions

### Q2.1 — Realtime Systems (10 Marks)

Identify which features require realtime communication.

Explain why polling every 10 minutes would fail for this platform.

---

### Q2.2 — API Architecture (10 Marks)

Explain why APIs are critical in this system.

Which systems communicate using APIs?

---

### Q2.3 — Stack Selection (10 Marks)

Choose the best stack for this platform and justify your answer.

Discuss:

- scalability
- realtime capabilities
- mobile support
- developer ecosystem

---

### Q2.4 — Database Strategy (10 Marks)

Explain what data belongs in:

- SQL databases
- NoSQL databases
- Cache systems

Provide examples.

---

### Q2.5 — High-Level Design (10 Marks)

Draw a high-level architecture diagram showing:

- mobile apps
- backend services
- APIs
- databases
- realtime communication layer

---

# Case Study 3 — Banking Payment Processing System

## Scenario

A bank processes SWIFT MT103 payment files.

Requirements:

- Incoming payment files from multiple banks
- Transaction validation
- Audit logging
- Secure storage
- Regulatory compliance
- Millions of records
- High reliability
- No transaction loss allowed

---

## Questions

### Q3.1 — Enterprise Architecture (10 Marks)

Explain why reliability is more important than UI design in this system.

Why are logs and audit trails critical?

---

### Q3.2 — Technology Selection (10 Marks)

Would you choose:

- Node.js
- Java
- .NET
- Python

Explain:

- strengths
- weaknesses
- enterprise suitability

---

### Q3.3 — Database Design (10 Marks)

Would MongoDB alone be sufficient for this platform?

Explain your answer.

Why are relational databases common in banking systems?

---

### Q3.4 — System Design (10 Marks)

Draw a high-level architecture showing:

- file ingestion
- parser
- validation service
- database
- reporting layer

---

### Q3.5 — Scalability & Reliability (10 Marks)

Explain how the system can handle:

- retries
- failures
- duplicate transactions
- high transaction volume

---

# Case Study 4 — College Learning Management System (LMS)

## Scenario

A college wants to build a Learning Management System with:

- student login
- assignments
- grades
- announcements
- quizzes
- discussion boards
- file uploads

Traffic spikes heavily during:

- exams
- assignment deadlines

---

## Questions

### Q4.1 — Application Architecture (10 Marks)

Identify the:

- frontend layer
- backend layer
- database layer

Explain the role of each.

---

### Q4.2 — Framework Selection (10 Marks)

Would Angular make more sense than React for this project?

Explain your reasoning.

---

### Q4.3 — Database Relationships (10 Marks)

Explain relationships between:

- students
- instructors
- courses
- assignments
- grades

Would SQL be important here?
Why?

---

### Q4.4 — Authentication & APIs (10 Marks)

Explain how APIs may be used in this system.

Why is authentication critical?

---

### Q4.5 — Scaling Considerations (10 Marks)

Explain:

- caching opportunities
- read-heavy operations
- performance bottlenecks

---

# Case Study 5 — IoT Smart Home Monitoring Platform

## Scenario

A smart home company sells:

- cameras
- thermostats
- door sensors
- motion detectors

Devices continuously send data to cloud servers.

Users can:

- monitor devices live
- receive alerts
- view historical data

---

## Questions

### Q5.1 — Realtime Systems (10 Marks)

Is this a realtime or batch system?

Explain your reasoning.

---

### Q5.2 — APIs & Communication (10 Marks)

Why are APIs critical for IoT systems?

What challenges appear when millions of devices connect simultaneously?

---

### Q5.3 — Database Selection (10 Marks)

Identify examples of:

- time-series data
- relational data
- unstructured data

Would NoSQL help?
Why?

---

### Q5.4 — Stack Selection (10 Marks)

Would Python or Node.js be useful for this system?

Explain your reasoning.

---

### Q5.5 — Architecture Design (10 Marks)

Draw a high-level architecture showing:

- IoT devices
- API gateway
- backend services
- databases
- notification systems

---

