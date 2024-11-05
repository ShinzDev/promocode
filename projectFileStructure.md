my-social-aggregator/
├── public/                       # Public assets like images, icons
│   ├── icons/
│   └── logo.png
├── src/                          # Main source directory
│   ├── components/               # Reusable components
│   │   ├── Feed.js               # Displays social media posts
│   │   ├── PostCard.js           # Individual post component
│   │   ├── SearchBar.js          # Search and filter component
│   │   └── BookmarkButton.js     # Bookmark functionality component
│   ├── hooks/                    # Custom hooks for reusable logic
│   │   └── useBookmarks.js       # Hook for managing bookmarks and local storage
│   ├── pages/                    # Next.js pages directory
│   │   ├── _app.js               # Global app configuration
│   │   ├── index.js              # Home page (main feed)
│   │   ├── bookmarks.js          # Bookmarks page
│   │   └── api/                  # API routes
│   │       └── posts.js          # Fetch posts from Instagram, TikTok, etc.
│   ├── styles/                   # Global and component styles
│   │   ├── globals.css           # Global styles
│   │   └── Feed.module.css       # Feed-specific styles
│   ├── utils/                    # Utility functions and helper scripts
│   │   ├── apiHelpers.js         # Functions for API requests
│   │   └── regexHelpers.js       # Regex for detecting promo codes
│   └── context/                  # Context API for state management
│       └── BookmarkContext.js    # Context for managing bookmarks
├── .env                          # Environment variables (API keys, secrets)
├── .gitignore
├── next.config.js                # Next.js configuration
├── package.json
└── README.md
