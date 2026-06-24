# Legal Document Review Agent

This workflow describes a high-level agentic AI pattern for reviewing legal documents with human oversight.

The purpose of this agent is not to provide final legal advice. It is designed to support lawyers, legal professionals, SMEs, and legal teams by summarizing documents, extracting important clauses, and flagging potential risks for human review.

---

## Workflow Objective

Help users understand legal documents faster by providing a structured review output.

The agent should support:

- Document summarization
- Clause extraction
- Risk flagging
- Missing clause identification
- Plain-language explanation
- Questions for legal review
- Human-in-the-loop approval

---

## Target Users

This workflow may support:

- Lawyers
- Small law firms
- Legal consultants
- SMEs
- Startup founders
- Contract managers
- Compliance teams

---

## Agent Responsibilities

The Legal Document Review Agent may perform the following tasks:

1. Identify the document type
2. Extract key parties
3. Extract important dates
4. Summarize the document
5. Identify key obligations
6. Extract major clauses
7. Flag risky or unclear terms
8. Identify missing clauses
9. Prepare questions for legal review
10. Recommend human expert review for high-risk items

---

## High-Level Workflow

```text
User uploads legal document
  ↓
Agent identifies document type
  ↓
Agent extracts key information
  ↓
Agent summarizes document
  ↓
Agent identifies clauses and obligations
  ↓
Agent flags risks
  ↓
Agent prepares review summary
  ↓
Human legal professional reviews output
  ↓
Final user-facing output is approved
