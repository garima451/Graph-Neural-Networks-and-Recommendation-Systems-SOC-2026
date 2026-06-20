# Ques-2 Solution

## What is a Knowledge Graph?

A **Knowledge Graph (KG)** is a structured representation of knowledge where **entities** (such as people, places, objects, or concepts) are represented as **nodes**, and the relationships between them are represented as **edges** in a graph.

Rather than storing information as isolated records, a knowledge graph captures how different pieces of information are connected, enabling machines to reason about relationships and discover new insights.

### Formal Definition

According to William L. Hamilton's *Graph Representation Learning*:

> A knowledge graph is a graph-structured knowledge base where nodes correspond to entities and edges correspond to relations between entities.

Knowledge graphs are often represented as **triples**:

```text
(Subject, Relation, Object)
```

For example:

```text
(Albert Einstein, born_in, Ulm)
(Ulm, located_in, Germany)
```

These triples collectively form a graph of interconnected facts.

## Key Components

### 1. Entities (Nodes)

Entities are the objects or concepts being represented.

Examples:

* Albert Einstein
* Germany
* Artificial Intelligence

### 2. Relations (Edges)

Relations describe how entities are connected.

Examples:

* born_in
* located_in
* works_for

### 3. Facts (Triples)

A fact combines two entities through a relation:

```text
(Apple, founded_by, Steve Jobs)
```

## Example Knowledge Graph

```text
Albert Einstein ── born_in ──► Ulm
Ulm ── located_in ──► Germany
Albert Einstein ── profession ──► Physicist
```

This graph structure enables a system to infer additional knowledge, such as the country associated with Albert Einstein's birthplace.

## Summary

A **Knowledge Graph** is a graph-based representation of real-world knowledge where entities are nodes and relationships are edges. By modeling how facts are connected, knowledge graphs enable machines to organize, retrieve, and reason over information more effectively than traditional tabular databases.
