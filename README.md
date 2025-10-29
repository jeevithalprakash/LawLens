Project Summary
LawLens is an AI-driven legal guidance platform tailored for the Indian audience, simplifying access to legal information through an intuitive AI legal assistant. It provides personalized legal advice, enabling users to navigate constitutional articles, state laws, and their rights effectively. By enhancing accessibility to legal resources, LawLens empowers individuals to tackle their legal challenges with confidence and clarity.

Project Module Description
AI Question Interface: Users can ask legal questions and receive tailored responses in professional English.
Constitution Search: Enables users to search and explore Indian constitutional articles and amendments.
State Laws Database: Provides access to state-specific laws and their descriptions relevant to Indian law.
Rights Explainer: Offers clear explanations of common legal rights within the Indian context.
Legal Aid Locator: Assists users in finding legal aid services based on their geographical location.

Directory Tree
shadcn-ui/
├── README.md
├── components/
│   ├── AIQuestionInterface.tsx
│   ├── ConstitutionSearch.tsx
│   ├── LegalAidLocator.tsx
│   ├── Navigation.tsx
│   ├── RightsExplainer.tsx
│   ├── StateLaws.tsx
│   └── ui/
│       ├── accordion.tsx
│       ├── alert-dialog.tsx
│       ├── alert.tsx
│       ├── button.tsx
│       ├── input.tsx
│       └── ...
├── data/
│   └── indianLegalData.ts
├── hooks/
│   ├── use-mobile.tsx
│   └── use-toast.ts
├── pages/
│   └── Index.tsx
├── public/
│   ├── favicon.svg
│   ├── robots.txt
│   └── assets/
│       └── lawlens-logo.jpg
├── src/
│   ├── App.css
│   ├── App.tsx
│   ├── index.css
│   └── main.tsx
├── package.json
└── vite.config.ts

File Description Inventory
README.md: Project documentation and setup instructions.
components/: UI components used throughout the application.
data/indianLegalData.ts: Contains structures for Indian legal data and AI response functions.
hooks/: Custom hooks for mobile responsiveness and notifications.
pages/Index.tsx: Main entry point for the application displaying various sections.
public/: Includes static assets like favicon and logo.
src/: Source files including styles and main application logic.
package.json: Lists project dependencies and scripts.
vite.config.ts: Configuration for the Vite build tool.

Technology Stack
React
TypeScript
Vite
Tailwind CSS
Shadcn-UI components
Lucide Icons
Usage
Install dependencies: pnpm install
Run linting: pnpm run lint
Build the project: pnpm run build

