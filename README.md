# backend-engineering-roadmap
Phase 0 – Engineering Mindset (2 Days)

Before touching Java.

Topics
How computers work
CPU
Memory
Process
Thread
Program
Compiler
Interpreter
Virtual Machine
Operating System
How Internet works
How servers work

Why?

Because every future topic depends on these.

Phase 1 – Java Language Mastery (20 Days)
Module 1
Java History
Why Java?
WORA
Bytecode
Evolution from Java 1 → Java 21
LTS releases
JVM Ecosystem
Module 2

Java Execution

Every single step

Main.java
↓
Lexical Analysis
↓
Parser
↓
AST
↓
Semantic Analysis
↓
Bytecode Generation
↓
.class
↓
JVM
↓
Execution Engine
↓
Machine Code
↓
CPU
Module 3

JDK

JRE

JVM

ClassLoader

Execution Engine

JIT

HotSpot

Bytecode

javap

Class File Format

Module 4

Memory

Heap

Stack

Method Area

Metaspace

Native Stack

PC Register

Object Layout

References

Module 5

Garbage Collection

Young Generation

Old Generation

Minor GC

Major GC

Full GC

G1GC

ZGC

Shenandoah

Memory Leak

Heap Dump

Thread Dump

Module 6

Core Java

Everything

Object

Class

Interface

Abstract Class

Inheritance

Composition

Aggregation

Association

Records

Enums

Annotations

Reflection

Module 7

Collections

ArrayList

LinkedList

HashMap

TreeMap

ConcurrentHashMap

HashSet

TreeSet

PriorityQueue

Deque

BlockingQueue

CopyOnWriteArrayList

Internal implementation

OpenJDK source code

Module 8

Concurrency

Thread

Executor

ForkJoinPool

Locks

Synchronization

volatile

Atomic

CAS

CompletableFuture

Virtual Threads

Structured Concurrency

Scoped Values

Module 9

Java 21

Every feature

Why introduced

Trade-offs

Production usage

Migration

Phase 2 – DSA (Runs Daily)

Language

C++

Topics

Arrays

Strings

Hashing

Stack

Queue

Linked List

Binary Search

Heap

Trie

Trees

Graphs

Backtracking

Greedy

Dynamic Programming

Bit Manipulation

Math

Union Find

Segment Tree

Sliding Window

Two Pointer

Monotonic Stack

Topological Sort

Shortest Path

MST

Disjoint Set

500 carefully curated questions

Phase 3 – Software Engineering (10 Days)

Git

GitHub

Maven

JUnit 5

Mockito

Testcontainers

Code Coverage

SonarQube

Clean Code

Refactoring

SOLID

Design Principles

Phase 4 – Low-Level Design (20 Days)

OOP

Design Principles

Gang of Four Patterns

Creational

Structural

Behavioral

LLD Problems

Logger

ATM

Parking Lot

Elevator

Splitwise

Chess

BookMyShow

Food Delivery

Cab Booking

Inventory

Phase 5 – Spring Ecosystem (18 Days)

Spring Core

IoC

DI

Bean Lifecycle

BeanFactory

ApplicationContext

Spring Boot

Auto Configuration

Actuator

Spring MVC

REST

Validation

Exception Handling

Spring Data JPA

Hibernate

Transactions

Caching

Spring Security

OAuth2

JWT

Spring Cloud

OpenFeign

Config Server

Gateway

Circuit Breaker

Phase 6 – Database Engineering (18 Days)
SQL

PostgreSQL

MySQL

Oracle

Indexes

Execution Plan

Optimizer

Transactions

Isolation

MVCC

Deadlock

Partitioning

Replication

Sharding

Normalization

CAP

PACELC

NoSQL

MongoDB

Redis

ElasticSearch

OpenSearch

Cassandra

DynamoDB

ClickHouse

Neo4j (basics)

When to use each

Phase 7 – Networking (10 Days)

OSI

TCP/IP

TCP

UDP

HTTP

HTTPS

HTTP/2

HTTP/3

TLS

DNS

gRPC

REST

GraphQL

WebSocket

SSE

CDN

Load Balancer

Reverse Proxy

Nginx

API Gateway

Phase 8 – Distributed Systems (18 Days)

Distributed Computing

CAP

PACELC

Consistency

Availability

Partition Tolerance

Replication

Leader Election

Raft

Paxos (high level)

Sharding

Consistent Hashing

Distributed Lock

ZooKeeper

etcd

Idempotency

Saga

CQRS

Outbox Pattern

Event Sourcing

Snowflake IDs

Rate Limiter

Bloom Filter

Circuit Breaker

Bulkhead

Retry

Timeout

Phase 9 – Messaging (12 Days)

Kafka

RabbitMQ

ActiveMQ

SQS

SNS

Pub/Sub

Producer

Consumer

ISR

Offset

Transactions

Exactly Once

Kafka Streams

Spring Kafka

Performance tuning

Phase 10 – Cloud Native (20 Days)

Docker

Container Internals

Namespaces

cgroups

Images

Volumes

Networking

Compose

Podman (since you're using it)

Kubernetes

Pods

Deployments

ReplicaSets

StatefulSets

DaemonSets

Jobs

CronJobs

ConfigMap

Secrets

Service

Ingress

Helm

Autoscaling

Rolling Updates

Canary

Blue Green

Troubleshooting

AWS

IAM

EC2

S3

VPC

ALB

CloudFront

CloudWatch

Lambda

SNS

SQS

RDS

Aurora

DynamoDB

ElastiCache

EKS

ECS

Route53

Secrets Manager

Phase 11 – Observability (6 Days)

Logging

Metrics

Tracing

OpenTelemetry

Prometheus

Grafana

Jaeger

Alertmanager

SLI

SLO

SLA

Phase 12 – Security (8 Days)

Authentication

Authorization

OAuth2

OIDC

JWT

SAML

CORS

CSRF

XSS

SQL Injection

SSRF

Secrets

Encryption

mTLS

OWASP Top 10

Phase 13 – System Design (20 Days)

Notification System

URL Shortener

WhatsApp

Uber

Netflix

YouTube

Dropbox

Google Drive

Twitter/X

Instagram Feed

Payment Gateway

Search Engine

Food Delivery

Chat System

API Gateway

Distributed Cache

Rate Limiter

Design every system from scratch.

Phase 14 – Production Engineering (Runs Throughout)

Linux

JVM tuning

GC Logs

Heap Dump

Thread Dump

JFR

Async Profiler

Connection Pool

HikariCP

Database tuning

Performance debugging

Incident response

Phase 15 – Interview Mastery (Last 2 Weeks)

Resume

Behavioral

Leadership

Salary Negotiation

Company-wise preparation

Mock Interviews

📁 GitHub Projects
backend-engineering-roadmap
Notes
DSA
HLD
LLD
Cheat Sheets
Technology Notes
backend-projects

Production-grade projects:

Employee Management
Notification Service
URL Shortener
Chat Application
BookMyShow
Food Delivery
API Gateway
Distributed Cache
🧠 Technology Backlog (Living Document)

We'll keep adding new technologies as they come up.

Already on the list:

✅ Java 21
✅ OpenSearch
✅ ClickHouse
✅ Elasticsearch
✅ Redis
✅ Kafka
✅ RabbitMQ
✅ Podman
✅ Kubernetes
✅ AWS
✅ OpenTelemetry
✅ Prometheus
✅ Grafana

Future additions could include:

OpenAPI
Temporal
Debezium
Apache Pulsar
Apache Flink
Apache Iceberg
Envoy
Istio
eBPF
gVisor
Vector Databases
AI integration patterns for backend systems