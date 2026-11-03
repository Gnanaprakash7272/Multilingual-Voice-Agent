# Multilingual Voice Agent

A configurable voice agent that handles appointment confirmation,
rescheduling, and cancellation in Tamil, Hindi, and English.

## Problem
Clinics and service centers lose customers to unanswered calls and
spend hours on repetitive scheduling calls. Many customers speak
Tamil or Hindi, or mix languages, and English-only IVR fails them.

## Goals
- Understand Tamil, Hindi, English, and code-mixed messages
- Answer questions from a knowledge base (RAG)
- Check, book, reschedule, cancel appointments via a database tool
- Escalate to a human when unsure or the caller is upset
- Be config-driven: new business = new config file, no code change
- Add voice (speech-to-text, text-to-speech) after the text version works

## Non-Goals
- Thousands of concurrent calls
- Carrier-grade telephony
- 30+ CRM integrations

## Tech Stack
Python 3.10, uv, an LLM API, ChromaDB, SQLite, LangGraph, FastAPI

## Status
Phase 0: setup (in progress)

## Setup
(to be added)

## Results
(to be added after evaluation)