Orbital Insight: Autonomous Satellite Collision Avoidance System

--------------------------------------------------

OBJECTIVE
To design an autonomous system capable of detecting and preventing satellite collisions using real-time simulation and minimal human intervention.

--------------------------------------------------

PROBLEM
Increasing satellites and space debris create high collision risk. Existing systems rely on delayed human intervention.

--------------------------------------------------

SOLUTION
This system simulates:
- Satellite launch and deployment
- Orbital motion
- Collision detection
- Thruster-based avoidance
- Orbit recovery
- Real-time phone alerts

--------------------------------------------------

FEATURES
- 3D solar system + Earth orbit simulation
- Satellite & debris interaction
- Collision avoidance system
- Hybrid model (auto + manual)
- Phone alerts (ntfy)

--------------------------------------------------

TECH STACK
- Backend: FastAPI
- Frontend: Three.js
- Environment: Google Colab 
- Deployment: Cloudflare Tunnel
- Notifications: ntfy

--------------------------------------------------

INPUTS
- Satellite count (max 5)
- Debris count
- Orbit radius (visual parameter)
- Alert topic

--------------------------------------------------

OUTPUT
- Full simulation:
  launch → deploy → collision → avoidance → recovery
- Event logs
- Phone alerts

--------------------------------------------------

USE CASES
- Space agencies (ISRO, NASA, ESA)
- Satellite constellations
- Space debris monitoring

--------------------------------------------------

LIMITATIONS
- Simplified orbital physics
- No real satellite data
- Temporary public URL (Cloudflare session-based)

--------------------------------------------------

FUTURE SCOPE
- Real orbital physics
- AI trajectory optimization
- Live satellite data integration
- Permanent cloud deployment

--------------------------------------------------

HOW TO RUN
1. Open .ipynb in Google Colab
2. Run all cells
3. Start Cloudflare tunnel
4. Open generated link + /ui

--------------------------------------------------

PHONE ALERT SETUP
1. Install ntfy app
2. Subscribe to a topic
3. Enter same topic in UI
4. Test alert

--------------------------------------------------

REFERENCES & CREDITS

APIs (from problem statement):
- Satellite data / orbital simulation APIs (as provided in problem PDF)
- Collision detection logic derived from given problem context

Additional APIs used:
- ntfy (notification service)
- Cloudflare Tunnel (deployment)

Libraries & Frameworks:
- FastAPI
- Three.js
- Requests
- Uvicorn

Tools:
- Google Colab

AI Assistance:
AI tools were used for coding support, but system design, logic, and implementation were developed and understood by the team.

--------------------------------------------------

NOTE ON LIVE DEMO
The public link generated via Cloudflare Tunnel is temporary.
To access the live demo, please run the provided notebook to generate a fresh link.

--------------------------------------------------

CONCLUSION
Orbital Insight demonstrates a scalable approach to autonomous satellite collision avoidance combining simulation, automation, and real-time alerts.
