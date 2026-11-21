# Aleksandr Gvindiaev

**Software engineer in Las Vegas, Nevada · Open to junior backend and full-stack roles**

I build Node.js services and API integrations. My experience also includes TypeScript, React, authentication workflows, AWS operations, and production troubleshooting. I work part-time at Anunnak, supporting an AI-powered platform and its delivery workflows.

## Vector Trans | Logistics request portal

I built a logistics demo that takes a shipment request from a browser form to a Telegram chat. The Node.js endpoint validates the request and waits for Telegram to confirm delivery before the browser shows success. If delivery fails, the form keeps the user's input. The demo has a Russian interface and an English setup guide.

[Try the live demo](https://vector-trans.vercel.app) · [Read the request handler](https://github.com/Alexg7707/vector-trans/blob/main/request.js) · [See the tests](https://github.com/Alexg7707/vector-trans/blob/main/request.test.js) · [View CI runs](https://github.com/Alexg7707/vector-trans/actions/workflows/ci.yml)

**Try it locally:** Clone [vector-trans](https://github.com/Alexg7707/vector-trans) and run `npm test` with Node.js 22 or later. The tests simulate Telegram responses, so you can inspect delivery failures without credentials.

## Other engineering work

| Project | What I worked on |
| --- | --- |
| **Anunak** · private Node.js service | Health and readiness endpoints for a running service, Prometheus-format metrics, and a bounded history of HTTP requests. Tests cover shutdown and what happens to older entries when the history fills up. |
| **Patient Call Lab** · Python prototype | A LiveKit-based voice testing tool that pairs timestamped transcripts with audio so a reviewer can replay the relevant moment in a conversation. |

[Connect on LinkedIn](https://www.linkedin.com/in/aleksandr-gvindiaev-021341420/)
