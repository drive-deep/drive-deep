# 🚀 Prabhat Ranjan

**Senior Backend & Security Platform Engineer | Golang | AWS | Distributed Systems**


## 📄 Resume & CV

**[⬇️ Download Resume (PDF)](./resume_prabhat.pdf)** | **[📖 View Full Resume](/resume_prabhat.pdf)** | **[LinkedIn Profile](https://linkedin.com/in/prabhat-ranjan)**

---

## 💡 About Me

I'm a backend engineer with **5+ years** building high-performance, multi-tenant security platforms and real-time trading systems. I specialize in:

- **Multi-tenant SaaS architectures** at scale (1000+ tenants, sub-100ms latency)
- **High-throughput packet processing** and Linux network isolation
- **Event-driven microservices** on AWS (Lambda, Kafka, DynamoDB)
- **Fintech automation** (algorithmic trading, broker API integration)

I approach every system with a focus on **scalability, security, and observability**—from packet-level to cloud infrastructure.

---

## 🎯 Core Strengths

### Backend & Architecture
- Multi-tenant cloud SaaS design and optimization
- Microservices & event-driven architectures (Kafka, Lambda, RabbitMQ)
- API design (REST, gRPC, OAuth2, JWT)
- Database optimization (PostgreSQL, Redis, DynamoDB, InfluxDB)

### Golang & Systems Programming
- High-performance backend services in Golang (Gin, Fiber, Chi)
- Real-time data processing and low-latency systems
- Linux network namespaces, packet processing, and networking tools
- Concurrent systems design (goroutines, channels, worker pools)

### Cloud & Infrastructure
- **AWS:** Lambda, EC2, S3, RDS, DynamoDB, EKS, ECR, SQS, SNS, CloudWatch
- **Kubernetes & DevOps:** Docker, Helm, Terraform, GitHub Actions, ArgoCD
- **Observability:** Prometheus, Grafana, Jaeger, CloudWatch, ELK Stack

### Security & Compliance
- OAuth2.0, JWT, OpenID Connect, mTLS, TLS/SSL
- AWS IAM, role-based access control, API security
- Secure multi-tenant isolation and data encryption
- OWASP best practices, threat modeling

---

## 💼 Work Experience

### **Trellix (formerly FireEye) – Backend Engineer** | Sep 2022 – Present

**Multi-Tenant SOAR SaaS Platform**
- Architected and scaled SOAR (Security Orchestration, Automation & Response) platform to **1000+ enterprise tenants**
- Optimized alert processing pipeline: **60% faster** alert handling through intelligent batching and caching
- Designed PostgreSQL schemas with tenant isolation strategies and Redis caching layers
- Built secure REST APIs with OAuth2, JWT, and role-based access control
- Implemented Kafka-based event streaming for real-time threat intelligence correlation

**Microservices & Real-Time Processing**
- Developed high-performance microservices in Golang and Python
- Built serverless Lambda functions for automated incident response
- Implemented comprehensive monitoring with Prometheus and Grafana
- Designed observability stack with centralized logging and distributed tracing (Jaeger)

**Technical Leadership**
- Mentored SDE1–SDE2 engineers on system design, API patterns, and best practices
- Led code reviews focusing on performance, security, and maintainability
- Drove architectural improvements reducing infrastructure costs by 35%

### **FireEye – Associate Software Engineer** | Aug 2020 – Aug 2022

- Built serverless event pipelines using AWS Lambda and DynamoDB
  - Processed **millions of security events** daily with sub-second latency
  - Designed DynamoDB tables for high throughput and cost efficiency
- Developed CI/CD pipelines using GitHub Actions, Jenkins, and ArgoCD
  - **Reduced deployment time by 50%** through automation and infrastructure improvements
- Optimized data ingestion and processing
  - Improved event processing speed by **4x** using Kafka and concurrent workers
- Implemented automated testing and monitoring for reliability

### **Wijungle – Software Engineer** | [Previously]

**Multi-Tenant Virtual Firewall Platform**
- Designed and built multi-tenant virtual firewall platform in Golang
- Leveraged Linux network namespaces for strict tenant isolation
- Achieved **5x throughput improvement** via goroutine-based packet processing
- Built custom policy engine with real-time rule evaluation (<1ms latency)
- Implemented comprehensive telemetry and logging for observability
- Enabled enterprise-grade deployments supporting multi-million-dollar deals

---

## 🚀 Featured Projects

### **Multi-Tenant Virtual Firewall Platform**
On-premises virtual firewall supporting multiple virtual firewalls on a single Debian machine with tenant isolation, packet processing, and security policies.

**Tech Bash/Shell Scripts, Golang (optional CLI tools), iptables/nftables, Linux Namespaces, Debian OS
**Key Achievements:**
- Supports multiple virtual firewalls on single Debian machine (capacity depends on system resources: CPU, RAM, network)
- Deployed via shell scripts with iptables/nftables for packet processing
- Linux namespaces for strict virtual firewall isolation
- Sub-millisecond policy evaluation using kernel-level netfilter rules
[→ View on GitHub](https://github.com/drive-deep/waf)

### **SOAR Event Processing & Incident Response**
Microservices-based security alert aggregation, correlation, and automated response.

**Tech Stack:** Go, Python, Kafka, AWS Lambda, DynamoDB, Step Functions  
**Metrics:**
- Scales to **1000+ enterprises**
- **60% faster** alert handling vs. legacy system
- Multi-tenant isolation with strict data boundaries
- Real-time alert correlation and threat intelligence integration

[→ View on GitHub](https://github.com/drive-deep/task-microservice)

### **Algorithmic Trading System (TradeFlash)**
Real-time stock trading engine with multi-strategy support and broker integration.

**Tech Stack:** Go, Kafka, FastAPI, Redis, PostgreSQL, WebSocket  
**Features:**
- Real-time broker API integration (Kotak Neo, Zerodha Kite)
- Event-driven order processing pipeline
- Custom trading strategies with profit/loss thresholds
- Live market data streaming via WebSocket
- Backtesting framework with historical data
- Risk management (stop-loss, position sizing, max drawdown)

[→ View on GitHub](https://github.com/drive-deep/tradeflash)

---

## 🛠️ Tech Stack

**Languages:** Golang • Python • Java • JavaScript • Bash  
**Web Frameworks:** Gin • Fiber • Echo • Chi • FastAPI • Django  
**Databases:** PostgreSQL • Redis • DynamoDB • MongoDB • InfluxDB  
**Message Queues:** Kafka • RabbitMQ • NATS • AWS SQS/SNS  
**Cloud:** AWS (Lambda, EC2, S3, RDS, EKS, CloudWatch, DynamoDB)  
**DevOps:** Docker • Kubernetes • Terraform • Helm • GitHub Actions • ArgoCD • Jenkins  
**Observability:** Prometheus • Grafana • Jaeger • CloudWatch • ELK Stack  
**Security:** OAuth2 • JWT • mTLS • TLS/SSL • AWS IAM • OWASP  
**APIs:** REST • gRPC • GraphQL • OpenAPI/Swagger  

---

## 🏗️ System Design Approach

**My process for building scalable systems:**

1. **Requirements Analysis** – Identify scalability, latency, consistency, and security needs
2. **Architecture Design** – Choose between microservices, monolith, or event-driven based on constraints
3. **Performance PoC** – Benchmark, profile, and optimize before full implementation
4. **Hardening** – Add security, multi-tenancy, error handling, and recovery
5. **Observability** – Implement logging, metrics, tracing, and alerting
6. **Rollout Strategy** – Canary deployments, blue-green, feature flags, gradual rollout

---

## 📊 Key Metrics & Impact

| Project | Impact | Scale |
|---------|--------|-------|
| Multi-Tenant Firewall | 5x throughput, <100ms latency | 1000+ tenants |
| SOAR Platform | 60% faster alerts, 35% cost reduction | 1000+ enterprises |
| CI/CD Pipeline | 50% faster deployments | All microservices |
| Data Optimization | 4x processing speed | Millions of events/day |

---

## 🎓 Education

**Bachelor of Engineering – Electronics & Communication**  
Indian Institute of Information Technology (IIIT) Allahabad  
GPA: 7.90/10

---

## 🏆 Achievements

- **GitHub:** Pull Shark (x2), Pair Extraordinaire, Arctic Code Vault Contributor
- **LeetCode:** Competitive problem-solving with focus on system design
- **Open Source:** Active contributor to Go ecosystem projects

---

## 🔗 Let's Connect

🔗 **LinkedIn:** [linkedin.com/in/prabhat-ranjan-47078414a/](https://www.linkedin.com/in/prabhat-ranjan-47078414a/)  
💻 **GitHub:** [github.com/drive-deep](https://github.com/drive-deep)  
📩 **Email:** [rprabhat760@gmail.com](mailto:rprabhat760@gmail.com)  

---

**Building scalable, secure, high-performance systems. Always learning. Open to collaborating on backend challenges, fintech automation, and distributed systems.**
