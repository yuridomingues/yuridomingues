# TraceRAG Core

**Regression testing and evidence for retrieval-augmented generation systems.**

TraceRAG started from a practical question: when a RAG system changes, how do we know whether retrieval actually improved or silently regressed?

## Problem

A generated answer can look plausible even when the retrieval layer changed for the worse. Teams need a way to inspect the evidence behind a query and compare retrieval behavior across versions.

## What I built

- deterministic document ingestion;
- project-scoped collections;
- retrieval with source, chunk and distance;
- optional rejection threshold for weak evidence;
- deterministic abstention when context is insufficient;
- benchmarks with hit rate, MRR and source recall;
- FastAPI endpoints returning both answers and supporting evidence;
- automated tests and CI.

## Engineering focus

**Python · FastAPI · RAG · retrieval evaluation · embeddings · testing · CI**

A central design rule is that retrieval metrics do not prove final-answer correctness. They measure a specific layer of the system and should be interpreted accordingly.

## Repository

Public source: https://github.com/yuridomingues/tracerag-core
