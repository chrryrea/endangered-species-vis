Endangered African Elephant Population & Conservation: Visualizing Protection Impact\
Essential Question\
"How has the endangered population of African Elephants changed in protected vs. non-protected areas over the past roughly 30 years, and what does this reveal about conservation effectiveness on a greater scale?"\
Data Sources\

African Elephant Database

Source: AfricanElephantDatabase.org
Description: Global species population trends (1995-2016).
Usage: Core population tracking baseline.

IUCN Red List

Source: IUCNRedList.org
Description: Inventory of the global conservation status and extinction risk of biological species.
Usage: Supplemantary background context 

Great Elephant Census

Source: ElephantsWithoutBorders.org
Description: Massively funded census conducted in 2016
Usage: Backup cross-referenced data for 2016 populations.

Visualization Approaches

Interactive Population Tracker

Tech Stack: React + Recharts
Features:

Species selection dropdown
Protected vs. unprotected comparison
Timeline analysis (1995-2016)

Conservation Impact Dashboard

Tech Stack: React + Shadcn UI
Features:

Population metrics cards
Protection effectiveness indicators
Geographic distribution maps

Project Structure\
endangered-species-vis/\
├── data/\
│ ├── raw/ # Original datasets\
│ └── processed/ # Cleaned data\
├── src/\
│ ├── components/ # React components\
│ ├── utils/ # Data processing\
│ └── App.js # Main dashboard\
├── public/\
│ └── assets/\
└── package.json\
