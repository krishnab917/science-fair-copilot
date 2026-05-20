# ScienceFair Copilot

AI-powered science fair evaluator that scores student project ideas across 8 expert rubric dimensions.

## Features
- Submit a project idea with title, description, grade level, budget, and timeline
- AI evaluation across 8 dimensions: Scientific Validity, Feasibility, Originality, Engineering Complexity, Judge Appeal, Scalability, Data Quality, Failure Risk
- Materials analysis with real-world sourcing, cost estimates, and substitutes
- Results dashboard with scores, reasoning, and improvement suggestions

## Stack
React · Vite · Tailwind CSS · Express · PostgreSQL · Drizzle ORM · OpenAI

## Setup
1. Clone the repo
2. Run `pnpm install`
3. Set `DATABASE_URL` and OpenAI env vars
4. Run `pnpm --filter @workspace/db run push` to set up the database
5. Start the API: `pnpm --filter @workspace/api-server run dev`
6. Start the frontend: `pnpm --filter @workspace/science-fair-copilot run dev`
