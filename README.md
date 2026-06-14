### CAMPAIGN PILOT AI-BACKEND CODEBASE

### Multi-Agent AI Revenue Intelligence Engine

This repository contains the backend architecture powering CampaignPilot AI.

The backend transforms retailer customer data into actionable marketing campaigns using a specialized AI agent workflow.

---

## Core Philosophy

Most CRM platforms provide dashboards.

CampaignPilot AI provides decisions.

Instead of showing retailers data and expecting them to figure out what to do next, the platform analyzes customer behavior and recommends revenue-generating actions automatically.

---

##  Backend Architecture

```text
                Customer Data
                       │
                       ▼
          Customer Intelligence Layer
                       │
                       ▼
          Goal Interpreter Agent
                       │
                       ▼
              Audience Agent
                       │
                       ▼
              Content Agent
                       │
                       ▼
            Strategy Engine
                       │
                       ▼
            Campaign Generator
                       │
                       ▼
             Simulation Engine
                       │
                       ▼
                ROI Forecast
```

---

## AI Agent System

### Goal Interpreter Agent

Responsible for:

- Understanding user objectives
- Detecting campaign intent
- Extracting business goals

Example:

```text
Input:
"Win back inactive customers"

Output:
Campaign Intent:
Retention Campaign
```

---

### Audience Agent

Responsible for:

- Segment discovery
- Audience selection
- Revenue opportunity analysis

Example Segments:

- High Value Customers
- At Risk Customers
- Recent Buyers
- Weekend Shoppers

---

### Content Agent

Generates:

- Email copy
- SMS copy
- Campaign messaging
- Personalized communication strategies

---

### Strategy Engine

Calculates:

- Expected Revenue
- Conversion Potential
- Audience Impact
- Campaign Recommendations

---

## Customer Intelligence Layer

Automatically computes:

- Customer Lifetime Value
- Revenue Contribution
- Purchase Frequency
- Recency Analysis
- Behavioral Segmentation

---

##  Database Layer

Database:

- PostgreSQL (Neon)

ORM:

- Prisma

Entities:

- Customers
- Orders
- Campaigns
- Campaign Metrics
- Delivery Logs
- Segment Snapshots

---

## API Endpoints

### Data Ingestion

```http
POST /api/data/ingest
```

Upload customer and order datasets.

---

### Campaign Preview

```http
POST /api/campaigns/preview
```

Generate AI campaign recommendations.

---

### Campaign Generation

```http
POST /api/campaigns/generate
```

Create executable campaign strategies.

---

### Campaign Simulation

```http
POST /api/simulation/start
```

Run campaign performance simulations.

---

## Technology Stack

Core Backend:

- Next.js API Routes
- TypeScript
- Prisma ORM
- PostgreSQL

AI Layer:

- Google Gemini
- OpenRouter Integration
- Custom Agent Architecture

Infrastructure:

- Vercel
- Neon Database

---

## Scalability Vision

Future roadmap includes:

- Autonomous campaign execution
- Real-time customer scoring
- AI-powered journey orchestration
- Shopify live synchronization
- Multi-channel marketing automation
- Predictive churn prevention

---

## 👨‍💻 Developer

**Kamal Addithan Bhavani**

Built for the Xeno SDE Internship Challenge.

---

## 🎯 Mission

To transform CRM from a reporting tool into an AI-powered revenue copilot capable of understanding business goals and autonomously generating growth strategies.

## Screenshots

<img width="960" height="540" alt="Screenshot 2026-06-14 204116" src="https://github.com/user-attachments/assets/b811b85b-0ce9-4f9b-9796-98821e8fd60d" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204128" src="https://github.com/user-attachments/assets/f7412c51-b457-4a93-aa63-0e0697028cb2" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204200" src="https://github.com/user-attachments/assets/1d206f2d-2e78-4515-9c62-72276c771f93" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204218" src="https://github.com/user-attachments/assets/55aef118-f2de-4f4e-bb1b-99dca1a7090a" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204234" src="https://github.com/user-attachments/assets/75c2227e-5c83-434b-9268-37ebbba5d3d9" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204302" src="https://github.com/user-attachments/assets/1c4a2a1b-709b-47ac-8ba3-fe68283caa1d" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204318" src="https://github.com/user-attachments/assets/b0907d13-13d3-4b1b-96cd-59f7634c351d" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204328" src="https://github.com/user-attachments/assets/9b7e93ab-bdcc-4918-b92b-9f592e46b13a" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204342" src="https://github.com/user-attachments/assets/5e018c58-0814-4440-8afc-05c954447eb7" />
<img width="960" height="540" alt="Screenshot 2026-06-14 204353" src="https://github.com/user-attachments/assets/21b5cf5e-8ef9-441a-b29b-8f2a3304d211" />
<img width="947" height="535" alt="Screenshot 2026-06-14 204059" src="https://github.com/user-attachments/assets/0089830a-6650-41da-885a-b658f9f44306" />

