# Document Parsing Challenge

## Task

The first step is to clone this repo!

Write a simple application for the ingestion of documents for downstream tasks such as Q&A, summaries, storage, and more.

As a minimum, the application must:

- **Ingest a PDF document** — parse and extract the content (PDF provided in the repo)
- **Enable question answering** — allow a user to ask natural language questions about the ingested document and receive accurate, grounded responses.
- **Provide a simple interface** — this should be a basic, responsive web UI with built in security, styling and interactivity.

Beyond the minimum, consider how you might extend the application to handle scenarios such as multi-document ingestion, chunking strategies, summarisation, or citation of source passages. You are not expected to implement all of these, but demonstrating awareness of them (even in documentation) is valued.

Please also include a brief write-up covering:

- **Application overview** — what you built, the key design decisions, and any trade-offs made.
- **Next steps** — how you would take this from a local prototype to a production deployment, including infrastructure, scaling, and observability considerations.

Once complete, push your code back to the repo.

This is purposefully open-ended to see how you approach the problem, structure your code, and communicate your thinking.

## Must Haves

The following items must be included, with some flexibility:

- Use the Microsoft Agent Framework or OpenAI (as a proxy for Azure OpenAI) for LLM reasoning
- Backend must be written in Python or C# to comply with Microsoft Agent Framework (+ TypeScript if using OpenAI)
- Frontend must be written in TypeScript or JavaScript with a preference for TypeScript.
- Frontend framework should be React based with Next.js, Vite etc. with component libraries of your choosing (i.e. Shadcn, copilotkit, MUI)
- Agentic coding is encouraged — please include any prompts, tools, and agents used as part of your submission
