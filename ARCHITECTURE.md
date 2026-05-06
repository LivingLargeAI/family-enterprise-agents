# 🏗️ System Architecture

## Overview

Family Enterprise is a multi-agent AI system designed to run business operations.

---

## Core Flow

User / Control  
↓  
Comms Server (Messaging Layer)  
↓  
Routing Layer (Governor)  
↓  
Agents (Cash, Sterling, etc.)  
↓  
Execution (AI Models / Automation)  

---

## Components

### 1. Comms Server
- Handles agent-to-agent communication
- Message-based system (dispatch, reports, tasks)

### 2. Routing Layer (Governor)
- Decides which model to use
- Controls cost and execution rules

### 3. Agents
- Role-based AI entities
- Each has a defined identity and responsibility

### 4. Execution Layer
- Gemini (fast, cheap)
- Anthropic (deep reasoning)
- Ollama (local fallback)

---

## Design Principles

- Modular
- Scalable
- Cost-controlled
- Automation-first

---

## Goal

A system where AI agents coordinate to run real business operations.
