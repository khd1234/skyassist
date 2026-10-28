# SkyAssist

AI assistant for a fictional airline ("SkyAir"). Answers policy questions
(baggage, refunds, check-in) using RAG, with source citations.

## Status
Work in progress. Day 1: project skeleton, Postgres + pgvector, FastAPI health check.

## Planned stack
Next.js, FastAPI, LlamaIndex, PostgreSQL + pgvector, Redis, S3 + Lambda, OpenAI.

## Run locally
    docker compose up -d
    cd backend && pip install -r requirements-dev.txt
    uvicorn app.main:app --reload

## Data
All documents are fictional. No real airline or employer material is used.