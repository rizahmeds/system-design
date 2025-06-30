> [!NOTE]
> A System Design Interview usually lasts for 45-60 minutes.

# Phase 1: Requirements Clarification (5-8 minutes)
## Functional Requirements:

- What specific features need to be supported?
- What are the core use cases?
- What's the expected user behavior?

## Non-Functional Requirements:

- Scale: How many users? (Daily/Monthly active users)
- Performance: Latency requirements? (Read/Write heavy?)
- Availability: Uptime requirements? (99.9% vs 99.99%)
- Consistency: Strong vs Eventual consistency needs?

### Example Questions to Ask:

- "How many daily active users are we expecting?"
- "What's the read-to-write ratio?"
- "Do we need real-time features?"
- "What's the acceptable latency?"

# Phase 2: Capacity Estimation (3-5 minutes)
### Calculate:

- Storage requirements
- Bandwidth requirements
- Memory requirements
- QPS (Queries Per Second)

> [!TIP]
> Show your math on the whiteboard!

# Phase 3: High-Level Design (HLD) (15-20 minutes)
### Components to include:

- Load Balancers
- Web Servers
- Application Servers
- Databases (Primary/Replica)
- Caching layers
- CDN
- Message Queues
- APIs

> [!TIP]
> Draw the flow: User → Load Balancer → Web Server → App Server → Database

# Phase 4: Database Design (5-8 minutes)
### Choose database type:

- SQL vs NoSQL justification
- Schema design (if SQL)
- Partitioning/Sharding strategy

# Phase 5: Detailed Design (LLD) (10-15 minutes)
### Deep dive into:

- API design (REST endpoints)
- Algorithm choices
- Data structures
- Caching strategies
- Security considerations

# Phase 6: Scale & Handle Edge Cases (5-8 minutes)
### Address:

- Bottlenecks identification
- Scaling strategies
- Failure scenarios
- Monitoring & alerting

# FAANG-Specific Tips:
1. **Communication is Key** - Stay structured and communicative: talk through your ideas, ask clarifying questions, and use sound reasoning. 
2. **Start Simple, Then Scale** - Begin with basic architecture, then add complexity.
3. **Justify Every Decision** - Explain why you chose specific technologies.
4. **Think Like a Senior Engineer** - Consider operational aspects, monitoring, debugging.
