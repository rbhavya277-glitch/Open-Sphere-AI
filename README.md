# OpenSphere AI

**Turning public data into understandable, source-backed insights.**

Explore public air-quality data through interactive charts and filters, and ask an AI assistant questions whose answers are backed by cited sources.

> 🚧 **Status: early development.** The architecture and features below describe the project's direction. See [Current Status](#current-status) for what works today.

---

## About

OpenSphere AI is a hands-on data engineering and AI project that collects real-world data from public sources, cleans and stores it in a structured database, and makes it explorable through a web interface. An AI assistant using Retrieval-Augmented Generation (RAG) answers questions based on the stored data and related documents, and links each answer back to its original source.

## Initial Focus: Air Quality

Version 1 focuses on public air-quality data: pollutant measurements (such as PM2.5, PM10, NO₂, and O₃) across locations and time periods. Other public-data domains will be considered only after the collection, storage, and analysis pipeline works reliably.

**Planned data sources** (to be finalized):
- [OpenAQ](https://openaq.org/) — open air-quality measurements from around the world
- Government portals (for example, India's CPCB) — where accessible data is available

## Core Objectives

- **Data Collection:** Retrieve data from public APIs and government portals.
- **Data Engineering:** Clean, validate, and transform data into a consistent structure.
- **Data Storage:** Store structured datasets and related documents for reliable querying and retrieval.
- **Data Exploration:** Provide searchable datasets, filters, charts, and summaries.
- **AI-Powered Insights:** Use LLMs and RAG to generate answers grounded in the available data and documents.
- **Source Transparency:** Link insights to their original sources wherever possible.
- **Extensible Design:** Structure the code so new data domains can be added over time.

## Current Status

- [x] Repository and project setup
- [ ] Data ingestion from the first public API
- [ ] Data cleaning and validation pipeline
- [ ] Database schema and storage
- [ ] Backend API (Flask)
- [ ] Basic dashboard with charts and filters (React)
- [ ] Document embeddings and RAG-based assistant
- [ ] Source citations in AI answers
- [ ] Testing and deployment

## Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| Data collection | Python, public APIs | Fetch air-quality data |
| Data processing | Pandas | Clean, validate, and transform data |
| Storage | SQL database *(e.g., PostgreSQL or SQLite, TBD)* | Store structured datasets |
| Backend | Flask | Serve data and AI features through an API |
| Frontend | React, data visualization library | Interactive charts, filters, and search |
| AI | LLMs, embeddings, vector search | RAG-based question answering with sources |

## Project Structure

*Coming soon.*

## Getting Started

*Setup and installation instructions coming soon.*

## Screenshots / Architecture

*Diagrams and screenshots will be added as the project develops.*

## Learning Goals

OpenSphere AI is also a learning project covering software development, Git and GitHub, API integration, data engineering, database design, AI application development, testing, and deployment.

## Contributing

This is a personal learning project under active development. Suggestions and feedback are welcome through issues.

## License

*To be added.*
