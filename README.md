# sclshotcaller-live/
│
├── public/
│   ├── logo.png
│   ├── favicon.ico
│
├── src/
│   ├── app/                  # Next.js App Router
│   │   ├── layout.tsx
│   │   ├── page.tsx          # Home (live games)
│   │   ├── login/
│   │   │   └── page.tsx
│   │   ├── dashboard/
│   │   │   └── page.tsx
│   │   ├── game/
│   │   │   └── [id]/
│   │   │       └── page.tsx  # Individual game page
│   │   ├── leaderboard/
│   │   │   └── page.tsx
│   │   ├── profile/
│   │   │   └── page.tsx
│
│   ├── components/
│   │   ├── Navbar.tsx
│   │   ├── GameCard.tsx
│   │   ├── PredictionForm.tsx
│   │   ├── LeaderboardTable.tsx
│   │   ├── ScoreBadge.tsx
│
│   ├── lib/
│   │   ├── firebase.ts       # Firebase config
│   │   ├── api.ts            # External sports API logic
│   │   ├── scoring.ts        # Scoring engine
│
│   ├── hooks/
│   │   ├── useAuth.ts
│   │   ├── useGames.ts
│   │   ├── usePredictions.ts
│
│   ├── types/
│   │   ├── user.ts
│   │   ├── game.ts
│   │   ├── prediction.ts
│
│   ├── styles/
│   │   ├── globals.css
│
│   └── utils/
│       ├── formatTime.ts
│       ├── calculatePoints.ts
│
├── .env.local
├── package.json
├── tsconfig.json
├── README.md
