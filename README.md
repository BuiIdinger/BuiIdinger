# C++ Software Engineer

# Skills

## MEMORY

- Manual memory management in C and C++.
- Alignment, padding, and cache-friendly data structures.
- Understanding of virtual memory, paging, and TLB.

## CONCURRENCY

- Lock-free programming (ring buffers, atomic operations).
- Thread affinity and CPU pinning for performance.
- High-throughput multithreaded server design.

## NETWORKING

- Socket programming with epoll, io_uring, and kqueue.
- Zero-copy techniques to minimize syscalls.
- Designing WebSocket servers and distributed systems.

## OPERATING SYSTEMS

- Kernel-level concepts: syscalls, interrupts, scheduling.
- Familiarity with writing firmware and low-level drivers.
- Understanding of process vs thread models.

## DISTRIBUTED SYSTEMS

- Data sharding, replication, and partitioning.
- Experience with Cassandra, load balancing, and hotspots.
- Optimizing queries for scalability and fault tolerance.

## SECURITY

- TLS/SSL implementation knowledge.
- Secure API design and data protection.
- Awareness of vulnerabilities (buffer overflow, race conditions, etc).

## LANGUAGES

- Expert in C and C++ (STL, custom allocators, containers).

# Experience

## SurveyBlox Ltd. | Software Engineer & CEO

- API server programmed in C++. Using WebSockets for communication. Handling over 5000+ connections at peak time. Benchmarked code using flame graphs and perf which reduced bottlenecks. Multithreaded server allowing for high throughput.
- Website using Nuxt and VueJS, with Tailwind CSS. Pinia for state management. Nuxt I18n module for dynamic translation. Nuxt Content for support articles.
- Apache Cassandra along 10 globally distributed nodes with SSL/TLS. Optimizing tables around queries. Secured traffic using TLS and encryption at rest.
- Virtual machines on Oracle with Ubuntu. Load balancing with TLS and health checks. Disaster recovery plan in place.
- Managed code via Git/GitHub, planned development process using Jira.

# Projects

## Payment System Duplex

- Highly performative TCP duplex using io_uring.
- TLS using OpenSSL to meet compliance with payment industry laws.
- Integrates with POS systems over TCP and uses the ISO 8583 message format.
- Processes a high volume of payment messages efficiently.

## Buildinger WebSocket

- RFC-6455 compliant WebSocket server using io_uring and BoringSSL for TLS.
- Benchmarking with flame graphs and perf to improve latency.
- Integrated unit tests and the Autobahn test suite to eliminate potential RFC-6455 violations.
- Optimization down to CPU cache and memory alignment to reduce CPU cycles.

## Garage Door Automator

- C++ WebSocket backend with Nuxt frontend.
- CAT-6 Ethernet cable connected to garage door dry contact points from a 5V isolated switch, controlled by a Raspberry PI 5 GPIO.
- Local website to control the garage door via WebSocket connected to the PI 5.

## Router Firmware Hacking

- Dumped an old router firmware over UART.
- Created a mini OS to init network controllers, paging, LEDs, etc.
- Uploaded my own mini OS with logging over UART.

shaydenseymour@gmail.com
