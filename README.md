# ToDoc: RAG-Based LLM Web Service for Parenting Support

ToDoc is an **AI-powered parenting support web service** designed to help first-time parents access **reliable, context-aware, and personalized childcare guidance**. By integrating **Large Language Models (LLMs)** with **Retrieval-Augmented Generation (RAG)** and **child-specific records**, ToDoc aims to reduce information overload and uncertainty in parental decision-making. http://todoc.ai.kr

<div align="center">
  <img src="https://github.com/user-attachments/assets/45dd78ca-9307-4e3e-b0f6-512d20cc0c2f"
       alt="Team2_홍보포스터"
       width="49%" />
  <img src="https://github.com/user-attachments/assets/a8b0e146-4fca-41b3-884f-5eca0f1d2f68"
       alt="Team2_학술포스터"
       width="49%" />
</div>

---

## Project Motivation

Modern parents—especially dual-income households—face increasing cognitive and emotional burdens when making childcare-related decisions.  
They must continuously assess issues related to a child’s **health, development, nutrition, and daily habits**, often relying on fragmented information from search engines, social media, and online parenting communities.

However, existing digital parenting services suffer from several limitations:

- Lack of **source credibility**
- Fragmented and inconsistent content across platforms
- Limited ability to reflect **individual child contexts**
- Overly generic LLM-based Q&A responses, especially risky in medical domains

To address these challenges, we propose **ToDoc**, an AI-based parenting support platform that combines **trusted public data**, **long-term personal child records**, and **agent-based LLM reasoning** within an HCI-driven system design.

---

## System Overview

ToDoc is built around three core components that form a unified service flow:

1. **Role-based AI Counseling (ToDoc AI)**
2. **Parent Community**
3. **Childcare Recording Diary (Personal Records)**

<img width="1014" height="791" alt="image" src="https://github.com/user-attachments/assets/00710218-51c8-4da4-9828-0dc636b21879" />

---

## 1. Role-Based AI Counseling (ToDoc AI)

The AI counseling feature is the primary interaction interface of ToDoc.  
It provides **real-time responses** to parents’ daily questions using three specialized AI roles:

- **Mom AI** – emotional support and empathetic guidance  
- **Doctor AI** – cautious, evidence-based medical information  
- **Nutrition AI** – dietary and nutrition-related recommendations  
ToDoc adopts this approach by allowing parents to **select the AI perspective** that best fits their situation and intent.

### RAG-Based Knowledge Integration

Each AI role uses a **separate RAG document pool**, sourced from trusted public institutions.

This design achieves:

- Reduced retrieval scope → faster response time
- Role-specific expertise → higher answer relevance
- Improved factual grounding → increased reliability

Childcare journal records are injected into the prompt context, enabling **personalized and situation-aware responses**.

### Prompt Engineering and Response Strategy

Each AI role emphasizes empathy, reassurance, and emotional tone.   
This differentiation allows parents to receive advice that is not only correct, but also **psychologically appropriate** for high-stakes caregiving scenarios.

---

## 2. Parent Community

The community feature provides a **social interaction space** where parents can:

- Share experiences and childcare tips
- Exchange used childcare products
- Engage in discussions with parents in similar life contexts

High-engagement community content can be selectively referenced by the AI counseling agents, allowing collective parental knowledge to inform future responses.

---

## 3. Childcare Recording Diary (Personal Records)

The childcare journal enables parents to **systematically log** their child’s:

- Growth milestones
- Health history
- Daily routines and behavioral patterns

### Role in Personalization

Long-term personal records play a crucial role in:

- Capturing developmental trends
- Supporting context-aware AI reasoning
- Enabling longitudinal decision-making rather than event-based reactions

These records are directly linked to the AI counseling system, forming the foundation of **data-driven personalization** in ToDoc.

---

## User Study

To evaluate usability and perceived value, a **one-week demo deployment** was conducted from December 7–13, 2025.

### Study Results

- Participants: 29 parents
- Recruitment channel: Online parenting community
- Evaluation method: 5-point Likert scale survey

- Overall satisfaction: **3.41 / 5**
- Goal achievement score: **3.13 / 5**
- Positive feedback:
  - Fast, context-aware AI responses
  - High relevance of advice reflecting personal records
  - Strong performance in health, behavior, and nutrition queries
- Identified limitations:
  - Inconsistent response latency
  - Insufficient emotional expressiveness, especially in Mom AI

These findings highlight that **emotional interaction design** is as critical as functional accuracy in parenting support systems.

---

## Key Contributions

- Demonstrates the feasibility of **context-aware AI parenting support** using RAG and LLM agents
- Shows that **data-driven personalization** significantly improves trust and acceptance
- Provides an HCI-oriented system design integrating AI counseling, personal records, and social interaction
- Identifies emotional expressiveness as a key future direction for caregiving AI

---

## Future Work

- Long-term user experience evaluation
- Enhanced emotional expression modeling for LLM agents
- Improved response latency consistency
- Expansion toward a sustainable AI–parent co-growth ecosystem

---
