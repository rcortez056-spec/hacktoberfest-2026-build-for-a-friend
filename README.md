# Private Local Text Triage Agent

> Built for Hacktoberfest 2026 Launch Weekend Challenge: **Build for a Friend**

## Overview
An offline-first, privacy-focused agent pipeline designed to parse sensitive unstructured notes and client communications using open-weight Gemma inference. This setup guarantees complete data sovereignty and zero cloud model dependencies.

## Key Features
- **Data Sovereignty:** Operates strictly on local hardware with open-weight models.
- **Schema Validation:** Strict JSON schema enforcement for downstream automation.
- **Task Decomposition:** Separates ingestion, inference, and structured output formatting.

## Repository Contents
- `schema.json`: JSON Schema definition for inputs and outputs.
- `system_prompt.txt`: Production prompt for local Gemma model execution.

## Submission Details
- **Challenge:** Hacktoberfest Weekend Challenge 1 (Build for a Friend)
- **Target Category:** Best Use of Gemma
- **Primary Repository:** rcortez056-spec
