# AI Video Ad Generator (n8n + AI Agents)

This project is an automated AI marketing pipeline built using **n8n**.

The system researches a company, identifies customer pain points, generates ad ideas using AI agents, and produces a short marketing video using the HeyGen API.

---

## Features

- Automated company research using Tavily
- AI-generated ad ideas and hooks
- AI storyboard generation
- Scene creation
- Video generation via HeyGen API
- Google Drive storage
- Google Sheets logging
- Used MCP server and created the whole workflow and in particularly using Antigravity.
---

## Workflow

Company Domain  
↓  
Tavily Research  
↓  
AI Agent – Ad Hook  
↓  
AI Agent – Storyboard  
↓  
Scene Generator  
↓  
HeyGen API Video Generation  
↓  
Google Drive Save  
↓  
Google Sheets Logging

---
## Workflow Architecture

The automation pipeline works as follows:

1. User inputs a company domain.
2. Tavily searches the web for product information.
3. Tavily researches ICP (Ideal Customer Profile) and pain points.
4. AI Agent generates marketing hooks and ad ideas.
5. AI Agent creates a storyboard for a short ad.
6. Scenes are automatically broken down.
7. HeyGen API generates video scenes with a consistent avatar.
8. Scenes are stitched into a single marketing video.
9. Final output is saved to Google Drive.
10. Logs are stored in Google Sheets.

---


## Tech Stack

- n8n
- Gemini / OpenRouter
- Tavily
- HeyGen API
- Google Drive API
- Google Sheets API
- Antigravity
- MCP Servers
---

## Demo

See demo video inside Workflow Demo Video.

---

## Author

Sharvan Mehta
