# AI Voice Interviewer Web Client

Frontend interface for the real-time AI Voice Interview platform, connecting to the Rust Axum backend.

## Overview

The client provides candidate-facing audio interview rooms, audio visualizers, live transcript rendering, and an administrative scorecard console.

## Features

* Real-time microphone capture and audio streaming over WebSockets
* Live audio visualization during conversational turns
* Candidate application flow with resume upload
* Recruiter dashboard for reviewing evaluations and scorecard metrics

## Tech Stack

* Next.js
* React
* TypeScript
* Tailwind CSS
* Web Audio API / WebSockets

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Configure environment variables:

Create a `.env.local` file pointing to the backend:

```ini
NEXT_PUBLIC_API_URL=http://localhost:8787
NEXT_PUBLIC_WS_URL=ws://localhost:8787/api/interview/ws
```

3. Run development server:

```bash
npm run dev
```