TON QuestLand Frontend Project Structure
----------------------------------------

src/
├── api/
│   ├── auth.js            # Handles user authentication API calls
│   ├── quests.js          # Handles API calls related to quests
│   ├── rewards.js         # Handles API calls for rewards and balances
│   └── index.js           # Central export for all API functions
│
├── assets/
│   ├── icons/             # Contains SVG/PNG icons
│   ├── images/            # Contains app images like banners or logos
│   ├── fonts/             # Custom fonts used in the app
│   └── README.md          # Describes how to add new assets and organize them
│
├── components/
│   ├── Button/            # Custom button components
│   │   ├── Button.jsx
│   │   ├── Button.module.scss
│   │   └── index.js
│   ├── Card/              # Card components for quests or rewards
│   │   ├── Card.jsx
│   │   ├── Card.module.scss
│   │   └── index.js
│   ├── Loader/            # Loading spinner
│   │   ├── Loader.jsx
│   │   └── Loader.module.scss
│   └── README.md          # Describes components and their usage
│
├── context/
│   ├── AuthContext.js     # Provides user authentication state
│   ├── QuestContext.js    # Manages active quest data
│   └── index.js           # Central export for all context providers
│
├── hooks/
│   ├── useAuth.js         # Hook for authentication logic
│   ├── useFetch.js        # Hook for API data fetching
│   ├── useGeoLocation.js  # Hook to manage user geolocation
│   └── README.md          # Guidelines for creating custom hooks
│
├── pages/
│   ├── HomePage/
│   │   ├── HomePage.jsx
│   │   ├── HomePage.module.scss
│   │   └── index.js
│   ├── QuestPage/
│   │   ├── QuestPage.jsx
│   │   ├── QuestPage.module.scss
│   │   └── index.js
│   ├── RewardsPage/
│   │   ├── RewardsPage.jsx
│   │   ├── RewardsPage.module.scss
│   │   └── index.js
│   ├── MarketplacePage/
│   │   ├── MarketplacePage.jsx
│   │   ├── MarketplacePage.module.scss
│   │   └── index.js
│   └── README.md          # Describes page structure and conventions
│
├── routes/
│   ├── AppRoutes.js       # Main route definitions for the app
│   ├── ProtectedRoute.js  # HOC to protect authenticated routes
│   └── README.md          # Documentation for managing routes
│
├── styles/
│   ├── global.scss        # Global styles for the application
│   ├── variables.scss     # CSS variables for consistent theming
│   └── README.md          # Style guidelines and conventions
│
├── utils/
│   ├── formatDate.js      # Utility to format dates for display
│   ├── storage.js         # Wrapper functions for localStorage/sessionStorage
│   ├── errorHandler.js    # Centralized error handling
│   └── README.md          # Overview of utility functions
│
├── App.js                 # Main application component
├── index.js               # React DOM rendering and app entry point
├── README.md              # Project overview and setup instructions
└── package.json           # Dependencies and project scripts
