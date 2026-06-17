# 2026 Project 11 — AI Platform

## Purpose

This project is part of the `AI-Engineering-Lab` learning roadmap.

It is the integration project of the roadmap. The goal is to assemble previous learning blocks into a small local AI platform.

This project should not be started too early. It depends on the understanding developed in local LLM serving, workflow automation, RAG, agents, vision, multimodal workflows, and robotics.

## Why this project exists

The previous projects build separate skills. This project combines them into a system:

```text
local LLM service
  ↓
workflow automation
  ↓
RAG service
  ↓
controlled agents
  ↓
monitoring
  ↓
applications / clients
```

The aim is not to build a large production platform immediately. The aim is to understand service boundaries, data flows, failure modes, and operational monitoring.

## Learning focus

This project focuses on:

- local AI platform architecture;
- model serving;
- service boundaries;
- workflow orchestration;
- RAG integration;
- controlled agents;
- monitoring;
- logging;
- deployment notes;
- failure modes.

## Minimal milestone

Draw and document the architecture of a minimal local AI platform with at least three services.

## Final deliverable

A minimal integrated platform with:

- a local LLM service;
- one workflow automation service;
- one RAG service;
- one controlled agent or assistant;
- basic logging and monitoring;
- documented data flows;
- documented failure modes.

## Repository structure

Recommended structure:

```text
architecture/      system diagrams and service boundaries
services/          individual platform services
docs/              operational notes
notes/             concepts and design decisions
monitoring/        logs, metrics, dashboards, checks
deployment/        local deployment notes
evaluations/       platform-level validation checklist
MENTORING.md       guided exercises and validation checklist
learning_log.md    session-by-session observations
```

## Success criteria

By the end of this project, I should be able to explain:

- what services exist in the platform;
- how data flows between them;
- which component owns which responsibility;
- how failures are detected;
- what is monitored;
- how the platform could evolve without becoming unmaintainable.

## Relation to the full roadmap

This project closes the first cycle of the `AI-Engineering-Lab` roadmap.

It should demonstrate that the previous projects were not isolated exercises, but reusable engineering blocks for building practical AI systems.
