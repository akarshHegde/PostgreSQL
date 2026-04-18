# PostgreSQL Study Fork

This repository is a PostgreSQL-focused learning fork that I used to explore database internals, concurrency behavior, indexing tradeoffs, and debugging techniques.

It is intentionally retained as a study artifact rather than presented as an original database implementation. The value of the repository is in the topics explored, the notes collected, and the way it captures hands-on systems investigation.

## Why this repository exists

I used this fork to build a practical understanding of how PostgreSQL behaves under the hood and to document concepts that are easy to discuss abstractly but much more useful when studied through code and experiments.

The repository covers topics such as:

- installation and environment setup
- hash index versus B-tree comparison
- MVCC behavior and concurrency control
- deadlock detection and correction concepts
- attaching GDB to PostgreSQL for debugging
- selectivity and index usage tradeoffs
- buffer replacement strategies such as LRU, MRU, Clock, and 2Q

## What I owned

My contribution in this repository was the learning workflow itself:

- studying PostgreSQL internals through the forked codebase
- documenting the concepts in a structured way
- collecting comparative notes and implementation observations
- producing supporting presentation material for the investigation

## How to navigate the repository

The supporting material is organized by topic and is intended to be read as a set of focused notes rather than as a standalone software product.

Key areas referenced in the original work include:

- `Postgres_Installation`
- `Index_Comparison`
- `MVCC`
- `Deadlocks`
- `Debug_Postgres_GDB`
- `Selectivity`
- `Buffer_Replacement_Policies`

## Public positioning

I keep this repository public because it reflects long-standing interest in systems and database internals. It should be read as a technical study archive, not as a current flagship portfolio project.

## Presentation artifacts

- YouTube: https://www.youtube.com/watch?v=JALu5dvNbCY
- Presentation: https://prezi.com/kxjj7glpe-13/postgres-team/
