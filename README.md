# Aurto2
PROJECT:THE AUTORIKSHA ODESSEY
                                                                                                                                                                                                   Overview
Autorickshaw Odyssey is a traffic survival simulation inspired by the unpredictable nature of city streets. The project recreates the experience of navigating through a constantly changing urban environment where obstacles, traffic, and weather conditions evolve over time.
Instead of fixed levels, the simulation focuses on creating a road that continuously changes as the player progresses. The goal is to move forward through the city while adapting to new challenges that appear along the way.

CONCEPT:
Cities are dynamic environments where situations change quickly. Traffic patterns shift, pedestrians appear unexpectedly, and weather conditions can suddenly interfere with movement.
This project attempts to simulate that experience by building a system where the environment gradually becomes more complex as distance increases. The longer the journey continues, the more unpredictable the road becomes.
Players are not completing levels — they are trying to survive an evolving city.

FEATURES:
1.Dynamic road simulation that avoids repetitive patterns
2.Increasing traffic density as the distance grows
3.Environmental obstacles such as potholes and barricades
4.Moving vehicles including buses, trucks, and bikes
5.Street elements like dogs crossing the road
6.Weather effects such as rain
7.Random environmental items like chai glasses or coins
These elements combine to create a city that feels active and constantly changing.

HOW IT WORKS:
The simulation generates road elements dynamically during gameplay. As the player progresses, the system gradually increases difficulty by introducing more traffic, obstacles, and environmental effects.
Different objects on the road are represented as structured data and updated continuously to create smooth movement and interaction within the scene.
The environment updates in real time, giving the impression of an ongoing and evolving city street.

TECH STACK:
Next.js – Application framework
React – UI and simulation logic
TypeScript – Structured data handling
Tailwind CSS – Styling and layout
ShadCN UI – Interface components

PROJECT STRUCTURE:
autorickshaw-odyssey
│
├── app/                # Main application pages
├── components/
│   ├── game/           # Simulation and game logic
│   └── ui/             # Interface components
│
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── public/             # Static assets
├── styles/             # Global styling
│
├── package.json
├── tsconfig.json
└── next.config.mjs
                                                                                                                                                                                            Running the Project
CLONE REPOSITORY
git clone <repository-url>
Navigate to the project directory
cd autorickshaw-odyssey
Install dependencies
pnpm install
Start the development server
pnpm dev
Open the application in your browser at
http://localhost:3000         
                                                                                                                                                                                                    Future Improvements
POSSIBLE IMPROVEMNETS INCLUDE:
2.Adding direct player controls for the autorickshaw
3.Expanding traffic behaviors
4.Introducing additional weather effects
5.Improving collision handling
6.Adding scoring and progression systems

LICENSE:
This project is intended for educational and demonstration purposes.
