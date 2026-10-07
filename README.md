# multi-crm-portal multi-crm-portal/
├── README.md                 # Setup & running instructions
├── frontend/
│   └── index.html            # Complete Single Page Application (HTML/CSS/JS)
└── backend/
    ├── package.json          # Node.js dependencies & scripts
    ├── server.js             # Express REST API (Deals, Appointments, Contacts)
    ├── .env.example          # Database configuration template
    └── prisma/
        └── schema.prisma     # PostgreSQL data models & relationships

        Frontend: Unzip and double-click frontend/index.html to open directly in any web browser.

Backend:

Navigate to backend/: cd multi-crm-portal/backend

Install dependencies: npm install

Set database URL in .env: cp .env.example .env

Apply database schema: npx prisma migrate dev --name init

Start local server: npm run dev
