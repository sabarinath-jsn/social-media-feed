Social Media Feed with Infinite Scrolling

A React-based social media feed implementing infinite scrolling to dynamically load additional posts as users scroll down.
Installation

    Clone the repo:

    bash

git clone https://github.com/your-username/social-media-feed.git

Install dependencies and start the server:

bash

    cd social-media-feed  
    npm install  
    npm start  

Key Features

    Infinite Scrolling: Uses IntersectionObserver to load more posts.
    Loading Optimization: Lazy loading and debouncing to improve performance.
    Loading Spinner: Displays a spinner while fetching new posts.
    Error Handling: Handles errors gracefully with fallbacks.

Challenges Addressed

    Optimized rendering with libraries like react-window for large datasets.
    Efficient API calls using a hasMore flag to detect the end of the feed.

Contributing

Fork the repository and submit a pull request for new features or improvements.
License

MIT License
