# Oracle Java Samples Repository
This repository provides Java samples for developers.

### List of Topics
1. [JDBC Basics](./topics/1-jdbc-basics.md) - Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa. Aenean et ornare lacus. 
2. [Pooling](./topics/2-pooling.md) -  Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa.
3. [Frameworks](./topics/3-frameworks.md) - Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa. Aenean et ornare lacus.
4. [AI/ML](./topics/3-frameworks.md) - Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa. Aenean et ornare lacus. Nam rhoncus mauris in elit fringilla tempor. 
5. [HA/DR](./topics/3-frameworks.md) - Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa. 
6. [Performance and Scalability](./topics/3-frameworks.md) - Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa. Aenean et ornare lacus. Nam rhoncus mauris in elit fringilla tempor. Vivamus enim est, tristique nec mauris vel, fermentum varius mauris.
7. [Diagnosability](./topics/3-frameworks.md) - Vivamus enim est, tristique nec mauris vel, fermentum varius mauris.
8. [Manageability](./topics/3-frameworks.md) - Vivamus enim est, tristique nec mauris vel, fermentum varius mauris.
9. [Security](./topics/3-frameworks.md) -  Vivamus enim est, tristique nec mauris vel, fermentum varius mauris. Lorem ipsum dolor sit amet, consectetur adipiscing elit. In eu leo egestas, dapibus eros ac, blandit massa.
10. [Integrations and Connectivity](./topics/3-frameworks.md) - Vivamus enim est, tristique nec mauris vel, fermentum varius mauris.

# List of Code Samples

| No. | Code Sample                                  | Description                                                                              |            Topics             | Features                                    |
|-----|----------------------------------------------|------------------------------------------------------------------------------------------|:-----------------------------:|:--------------------------------------------|
| 1   | [jdbc-hikaricp<sup>√</sup>]()                | Demonstrates use of basic Hikari CP configurations                                       |           `Pooling`           | HikariCP                                    |
| 2   | [jdbc-ucp]()                                 | Demonstrates use of basic UCP configurations                                             |           `Pooling`           | UCP                                         |
| 3   | [jdbc-ucp-hibernate]()                       | Demonstrates integration of UCP with Hibernate                                           |           `Pooling`           | UCP, Hibernate                              |
| 4   | [jdbc-data-types](./samples/jdbc-data-types) | Demonstrates all data types including new data types json, xml, boolean, vector and more |         `JDBC Basics`         | Core Data Types, JSON, XML, Boolean, Vector |
| 5   | [jdbc-assoc-array]()                         | Demonstrates use of associative arrays                                                   |         `JDBC Basics`         | Associative Arrays                          |
| 6   | [jdbc-callable-statements]()                 | Demonstrates use of Statements, Functions and Procedures                                 |         `JDBC Basics`         | Statements, Functions and Procedures        |
| 7   | [jdbc-cursors]()                             | Demonstrates in-depth use of cursors                                                     |         `JDBC Basics`         | Cursors and REF Cursors                     |
| 8   | [jdbc-large-blobs-and-streams]()             | Demonstrates working with large blobs and streaming                                      |         `JDBC Basics`         | Blobs, JAva Streams                         |
| 9   | [jdbc-batch-and-db-pipelines]()              | Demonstrates use of batch operations                                                     |         `JDBC Basics`         | Batch Operations and Database Pipelining    |
| 10  | [jdbc-perfect-timing]()                      | Demonstrates use of the time data type                                                   |         `JDBC Basics`         | Timestamp, Timestamp with Time Zone         |
| 11  | [ai-vector<sup>★</sup>]()                    | Demonstrates using the new Vector data types in a complex example                        |            `AI/ML`            | Vectors, AI                                 |
| 12  | [jdbc-application-continuity]()              | Demonstrates configuring Oracle JDBC for Application Continuity                          |            `HA/DR`            | Application Continuity                      |
| 13  | [spring-relational<sup>★</sup>]()            | Demonstrates JSON Relational Duality on top of Spring                                    |         `Frameworks`          | Spring Boot, JSON Relational Duality        |
| 14  | [spring-basic<sup>√</sup>]()                 | Demonstrates Basic spring example with working Oracle JDBC                               |         `Frameworks`          | Spring Boot                                 |
| 15  | [spring-jpa-hibernate]()                     | Demonstrates use of JPA with Oracle, with feature flags demonstrating Hibernate usage    |         `Frameworks`          | Spring, Spring JPA, Hibernate               |
| 16  | [rsi-micronaut]()                            | Demonstrates Reactive Streams Ingestion with a micronaut application                     | `Performance and Scalability` | RSI, Micronaut                              |
| 17  | [reactive-ucp<sup>★</sup>]()                 | Shows UCP Asynchronous Extensions                                                        | `Performance and Scalability` | UCP Async                                   |
| 18  | [jdbc-teq]()                                 | Demonstrates basic transactional event queues                                            | `Performance and Scalability` | TxEventQ                                    |

<sup>★</sup>New Database Feature: Version 23ai<br/>
<sup>√</sup>Deploy anytime (Kubernetes, Docker, or deploy scripts available)

# Feedback/Issues
Please submit your feedback or any issues on any code sample via GitHub issues.
