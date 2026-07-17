
# 🧠 Knowledge Graph Learning Framework

> **Learn concepts, not tutorials. Build a knowledge graph, not isolated notes.**

## 🎯 Goal

The purpose of this framework is to:

* Understand concepts instead of memorizing.
* Connect knowledge into a personal Knowledge Graph.
* Learn progressively without getting lost.
* Focus on high-ROI knowledge.
* Build strong mental models through continuous connections.

---

# 📌 Core Principles

### 1. One Concept = One Node

Each note represents **one concept only**.

Examples:

* Transaction
* MVCC
* Kafka
* Redis
* TCP

---

### 2. Finish the Current Node

If a new concept appears while learning:

```text
Transaction
    ↓
MVCC
```

Do **not** switch immediately.

Instead:

```text
TODO
- MVCC
```

Finish the current node first.

---

### 3. Build a Knowledge Graph

Knowledge should be connected, not isolated.

Each node should include:

* **Prerequisites** (0–5)
* **Related Concepts** (3–5)
* **Next Learning** (1–3)

Example:

```text
Transaction

Prerequisites
- ACID

Related
- Lock
- MVCC
- Isolation Level
- Saga

Next
- MVCC
- Deadlock
```

---

### 4. Learn in Context

Never learn a concept without knowing where it belongs.

Example:

```text
Distributed Systems
        ↓
Consensus
        ↓
Raft
```

Every node should have a parent topic.

---

# 📝 The 10 Questions Framework

Every node should answer these questions.

1. **Definition**
   What is it?

2. **Problem**
   Why does it exist? What problem does it solve?

3. **Mechanism**
   How does it work?

4. **Trade-offs**
   Advantages, disadvantages, costs.

5. **Applications**
   Where is it used?

6. **Dependencies**
   What concepts should I understand first?

7. **Relationships**
   Related concepts, alternatives, complementary technologies.

8. **Limitations**
   When should I NOT use it?

9. **Without It**
   What would happen if it didn't exist?

10. **Implementation**
    How is it implemented internally?

---

# 🌱 Learning Levels

Not every concept deserves the same depth.

## 🟢 Level 1 — Awareness

Know:

* What it is
* What problem it solves
* When it is useful

Examples:

* Bloom Filter
* Trie
* HyperLogLog

---

## 🟡 Level 2 — Working Knowledge

Understand enough to use it correctly.

Answer Questions **1–8**.

Examples:

* Redis
* JWT
* OAuth
* Docker

---

## 🔴 Level 3 — Deep Understanding

Understand implementation and internals.

Answer all **10 questions**.

Examples:

* Transaction
* MVCC
* HTTP
* TCP
* Kafka

---

# 📈 Choosing the Depth (ROI Rule)

Evaluate every concept using these five questions:

* Do I use it frequently?
* Does it unlock many other concepts?
* Is it valuable for interviews or system design?
* Is misunderstanding it likely to cause bugs?
* Does it have meaningful technical depth?

### Score

* **0–2** → Level 1
* **3** → Level 2
* **4–5** → Level 3

> **Depth follows value.**

---

# 🔄 Learning Flow

```text
Choose a Concept
        ↓
Answer the 10 Questions
        ↓
Encounter New Concepts
        ↓
Add Them to TODO
        ↓
Finish Current Node
        ↓
Learn the Next Node
        ↓
Connect the Nodes
        ↓
Repeat
```

---

# 🚫 Rabbit Hole Rule

When a new concept appears:

✅ Add it to your TODO list.

✅ Finish the current node.

❌ Never interrupt your learning flow to chase a new topic.

---

# ✅ Definition of Done

A node is complete when you can:

* Explain it without notes.
* Describe why it exists.
* Explain how it works.
* Discuss its trade-offs.
* Give real-world use cases.
* Explain when **not** to use it.
* Connect it to related concepts.
* Know how it is implemented (if Level 3).

If you cannot explain it simply, the node is **not** complete.

---

# 📖 Node Size

Keep every node concise.

Recommended:

* **300–800 words**
* **1–2 pages**
* Prioritize understanding over completeness.

---

# 🔁 Review

Review a node:

* After finishing its parent topic.
* Before interviews.
* Whenever it becomes relevant in real projects.

Update the node whenever your understanding improves.

---

# 🎯 Final Goal

The goal is **not** to collect hundreds of notes.

The goal is to build a **personal Knowledge Graph** where every concept is connected.

Eventually, learning a new technology is no longer starting from zero—it is simply connecting a new node to an existing graph.

> **Learn concepts. Build connections. Think in systems.**
