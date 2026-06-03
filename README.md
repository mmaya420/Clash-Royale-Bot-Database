# Clash Royale Bot Database

A relational database system designed for a Database Systems course at Fordham University.

## About
Models an ecosystem of AI bots deployed in Clash Royale, tracking developers, bot owners, users, and interaction history across 7 normalized tables.

## Features
- 7-table normalized schema with foreign key constraints
- Supertype/subtype table inheritance (Bot → ClashRoyaleBot)
- Many-to-many junction table for user-bot interaction tracking
- 8 analytical SQL queries using JOINs, GROUP BY, and aggregate functions (AVG, COUNT)

## Tech Stack
SQL, MySQL
