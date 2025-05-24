# Profeshare AI – MVP PRD v0.1

## 1. Problem
Job seekers waste hours scrolling; recruiters drown in spam. Conversational search fixes both.

## 2. Goal (6-week alpha)
*Students* can:  
1. Sign up and create a profile  
2. Ask a natural-language query → receive top 10 job matches  
3. Click a result → “Apply” or “Message recruiter”

*Recruiters* can:  
1. Sign up, create company & job post  
2. Search talent conversationally → view candidate cards  
3. Click “Present opportunity” → sends chat message & email

Success = 20 alpha testers complete at least one search + follow-up action.

## 3. Non-Goals
• Payments, recommendations, analytics dashboards, mobile app.

## 4. Personas
– Student “Asha” (final-year BTech, Hyderabad)  
– Recruiter “Rahul” (Campus hiring lead, mid-size SaaS)

## 5. User Stories
### Student
1. As a student, I want to …  
…
### Recruiter
1. As a recruiter, I want to …

## 6. User Flow Diagrams
(link to Figma)

## 7. Functional Spec
| Module | Description | Acceptance Criteria |
|--------|-------------|---------------------|
| Auth | Email/OTP … | … |

## 8. Tech Stack
* Front-end: Next.js (App Router)  
* Back-end: FastAPI / Supabase …  
* Vector search: pgvector …

## 9. Metrics
– Time-to-first-result < 3 s  
– Search precision@5 ≥ 0.6 (internal test set)  
…

## 10. Risks & Mitigations
1. LLM latency …  
2. Intern turnover …

## 11. Milestones
W0 Scope lock, W1 UX, W2-3 Backend+Search, W4 Front-end, W5 QA, W6 Alpha
