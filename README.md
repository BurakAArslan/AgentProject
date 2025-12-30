# AgentProject  
## SMART TRANSPORTATION & TRAFFIC OPTIMIZATION SYSTEM  
### ReAct + Multi-RAG + Live API Integration

---

## Project Overview

This project aims to develop a **ReAct (Reasoning + Acting)** based artificial intelligence agent that integrates **traffic safety**, **traffic regulations**, and **live traffic data** within the scope of **smart transportation systems**.

The system combines:

- PDF-based information retrieval (RAG)
- Live traffic APIs (TomTom)
- Mathematical reasoning
- Tool-forced decision-making mechanisms

to provide an architecture that guarantees the use of the **correct tool for the correct type of question**.

---

## Project Objectives

- Prevent hallucinations in traffic-related questions  
- Automatically switch to live APIs when static knowledge is insufficient  
- Orchestrate RAG, API, and Math tools in a controlled manner  
- Make the **Thought → Action → Observation** reasoning chain fully traceable  
- Produce measurable success rates for benchmark and demo queries  

---

## System Architecture

### ReAct Workflow

```text
THOUGHT
→ ACTION
→ OBSERVATION
→ FINAL ANSWER
