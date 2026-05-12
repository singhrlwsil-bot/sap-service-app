sap-service-app/
│
├── backend/                         # Node.js + Express backend
│   ├── src/
│   │   ├── routes/                  # API routes (download, signature, etc.)
│   │   ├── controllers/             # Business logic
│   │   ├── services/                # SAP integration services
│   │   └── utils/                   # Helper functions
│   ├── tests/                       # Unit tests
│   ├── Dockerfile                   # Docker build for backend
│   └── package.json                 # Node.js dependencies
│
├── frontend/                        # Flutter app (mobile + web)
│   ├── lib/
│   │   ├── screens/                 # UI screens (dashboard, signature, report)
│   │   ├── widgets/                 # Reusable components
│   │   └── services/                # API calls to backend
│   ├── assets/                      # Images, icons, fonts
│   ├── android/                     # Android build files
│   ├── ios/                         # iOS build files
│   ├── web/                         # Web build files (Flutter web support)
│   └── pubspec.yaml                 # Flutter dependencies
│
├── .github/
│   └── workflows/                   # CI/CD pipeline configs
│       ├── backend-ci.yml           # Backend build & deploy
│       ├── frontend-mobile-ci.yml   # Mobile build (APK/IPA)
│       └── frontend-web-ci.yml      # Web build (deploy to hosting)
│
├── docs/                            # Documentation
│   ├── architecture.md              # System architecture
│   ├── api-spec.md                  # API endpoint design
│   └── ci-cd-pipeline.md            # CI/CD pipeline details
│
└── README.md                        # Project overview
