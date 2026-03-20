⚽ The Mavericks | Squad & Tactics Manager

A professional-grade, data-driven tactical suite designed for The Mavericks soccer club to manage Wednesday and Saturday sessions. This application leverages the Gemini 2.5 Flash API for tactical scouting and Firebase Firestore for persistent league data.

🚀 Key Features
1. Smart Squad Registry
True Power Algorithm: Calculates player ratings by weighting self-assessment (40%) against anonymous community peer feedback (60%).
Multi-Factor Balancing: Automated team formation mathematically balances Technical Skill, Agility, and Age Factor.
✨ AI Player Bios: Generates a professional, gritty one-sentence scouting profile for every registered Maverick using the Gemini LLM.

2. Match Day & Tactical Engine
16-Player Gatekeeper: Deployment is locked until exactly 16 players (Registry + Guests) are confirmed to ensure a balanced 8-a-side match.
Position-Aware Shuffling: Teams are formed by shuffling position groups (GK, DEF, MID, FWD) individually before distribution to ensure no lopsided compositions.
Positional Field Mapping: A visual 1-2-3-2 formation map that anchors player icons to their specific registered primary positions.
✨ Coach Gemini Scout Report: Real-time tactical analysis of the current rosters, providing three gritty pre-match tips based on team parity.

3. League History & Analysis
Championship Tracking: Archives winning squad rosters, scores, and goal-scorer tallies.
MVP Consensus: Nominate a "Maverick of the Match" and allow the community to provide a 1-5 star performance rating in the History tab.
✨ Match Chronicles: Transforms simple scores into dramatic sports journalism recaps for social sharing.

4. Integration & Security
WhatsApp Sharing: One-tap formatting for Team Composition sheets and Post-Match Analysis reports.
Admin Mode: A hidden security layer (unlocked by tapping the Mavericks Logo 5 times) allowing for profile editing, record deletion, and core data restoration.

🛠 Tech Stack
Frontend: HTML5, Tailwind CSS, JavaScript (ES6 Modules)
Database & Auth: Firebase Firestore & Anonymous Authentication
AI Engine: Google Gemini 2.5 Flash API
Visuals: HTML5 Canvas API & Chart.js

📖 Usage Guide
For Players:
Register: Go to the Registry tab, enter your details, and set your skill sliders.
Rate Peers: Help the balancing engine by rating your teammates' technical skill and agility.
Check-In: On match day, find your name in the pool and toggle it to "Confirmed" once you arrive at the pitch.

For Organizers:
Deploy: Once 16 players are selected, tap Deploy Match Teams.
Share: Use the WhatsApp button to send the teams to the group chat.
Analyze: Tap ✨ AI Scout to get the pre-game tactical breakdown.
Record: After the match, enter the score and goal scorers in the Post-Match Results section.

🔧 Installation (GitHub Pages)
This is a single-file application designed for easy hosting:
Upload index.html and your logo file (Untitled design (1).png) to a GitHub repository.
Go to Settings > Pages and enable hosting from the main branch.
Add your Gemini API Key to the apiKey constant in the script section of index.html to enable AI features.
Generated for The Mavericks | Data-Driven Tactics
