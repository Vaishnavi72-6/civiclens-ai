
# CivicLens AI

## Why this project?
Document verification and eligibility checks for public services are often manual, opaque, and error-prone. Existing digital systems store documents but fail to reason over them or explain decisions transparently.

## What does CivicLens AI do?
CivicLens AI is an AI-driven backend platform that:
- Extracts structured data from documents
- Verifies document integrity
- Reasons eligibility using rule-based logic
- Generates explainable decisions with confidence scores
- Flags potential fraud patterns

## Key Engineering Highlights
- Explainable decision engine (not black-box AI)
- Clean separation of services (OCR, NLP, rules, fraud)
- API-first, scalable architecture
- Security-focused design using cryptographic hashing

## Tech Stack
- Python, FastAPI
- OCR + NLP
- PostgreSQL
- SHA-256 hashing

## Current Status
MVP under active development.
