# GenArch — AI-Powered Deterministic Text-to-Architecture Generation Pipeline

GenArch is an intelligent architecture synthesis and visualization system built using Python and structural constraint mapping.

The platform programmatically transforms unstructured natural language technical specifications into strict, schema-enforced UML class diagrams and design primitives.

GenArch eliminates the manual overhead developers spend using traditional drag-and-drop design tools. Instead of manually constructing charts box-by-box, engineers receive clean, vertically balanced architectural diagrams generated instantly from plain text.

---

# Project Overview

GenArch was developed to solve a common software engineering bottleneck:

> Maintaining up-to-date system documentation manually is time-consuming, and standard generative AI text-to-graphics implementations suffer from layout drift—where unconstrained parsing outputs sprawling node matrices that break canvas bounds and corrupt rendering syntax.

This project resolves this friction by combining:
- Contextual prompt framing
- Deterministic token-stream validation
- Server-side viewport enforcements
- Automated multi-topology compilation

The system intercepts messy raw strings, injects precise geometric boundaries into the context parser, filters out conversational syntax anomalies, and guarantees high-fidelity layouts that render perfectly without horizontal sprawl or canvas clipping.

---

# Supported Diagram Topologies

## Structural Architecture
- UML Class Diagrams
- System Component Hierarchies
- Data Models & Relationships

## Behavioral Blueprints
- Sequence Diagrams
- Use Case Diagrams
- Interaction Flows

---

# Key Features

- **Multi-Topology Synthesis:** Generates everything from object-oriented UML class structures to system sequence maps dynamically.
- **Deterministic Viewport Control:** Custom prompt constraints explicitly eliminate canvas overflow, horizontal drift, and syntax breaks.
- **Isolating Canvas Rendering:** Decouples core web application styles from generated vector buffers to export pristine visual documentation blocks.
- **State Handling & Workspace Management:** Natively tracks isolated user profiles and execution histories using a secure web session layer.
- **Engine Optimization Engine:** Sanitizes the response stream to strip away conversational prefixes and isolate pure, valid structural syntax.
- **Django-Powered Backend:** Built on a production-ready web application node for low latency and smooth request lifecycle management.

---

# How It Works

## Example Workflow — System Design Domain

### User Inputs
- Core System Architecture Prompt (e.g., *"Design a Crypto Wallet Tracker with 4 core classes..."*)
- Layout structural constraints

### System Process
1. Captures the raw system statement via the unified dashboard interface.
2. Programmatically appends rigid grid boundaries, structural schemas, and termination rules inside the orchestration views layer.
3. Dispatches the optimized payload to the underlying token parsing layer.
4. Catches, sanitizes, and filters the returned token stream to guarantee valid syntax execution.
5. Directs the clean execution blocks to the server-side compilation engine to render an isolated, high-resolution graphic asset.

---

# Data & Parsing Approach

The project leverages:
- Advanced contextual schema design for deterministic pipeline outputs.
- Rigorous token filtering algorithms to isolate structural data from text models.
- String serialization pipelines to strip conversational text mutations and vulnerabilities.

The core execution pipeline guarantees:
- Token-stream structural validation.
- Precise layout rendering and arrow-direction parsing.
- Scalable, zero-drag visual document synthesis.

---

# Tech Stack

## Programming Language
- Python 3.x

## Backend Web Architecture
- Django Framework

## API & Query Layer
- GraphQL (Structured system interaction and data schema processing)

## Image & Layout Compilation
- Pillow Canvas Engine
- Standalone Server-Side Layout Compiler

## Frontend Interface Layer
- HTML5, CSS3, Django Templates

---

# Output Screenshots

## Programmatic Diagram Generation
An example of an isolated, vertically constrained, high-readability UML class diagram output compiled seamlessly through the optimized prompt pipeline.

<img width="100%" alt="Generated Production UML Asset" src="media/output image.png">
