🌍 PlanetPulse — Environmental News Dashboard

PlanetPulse is a responsive and visually engaging web application that aggregates environmental news from various sources (mock data in this prototype). It helps users stay updated on climate change, sustainability efforts, and ecological developments through categorized articles, interactive charts, and bookmarking features.

This project is built using HTML, CSS, and JavaScript in a single-file structure for simplicity.

⭐ Features
✔️ Core Functional Requirements

Aggregate environmental news using mock data (easily replaceable with API/RSS feeds)

Display categorized articles by environmental topics (Energy, Forests, Oceans, etc.)

Trend visualizations powered by Chart.js

Search and filter news by keywords

Sort articles (Newest / Oldest)

Fully responsive layout with teal–green–blue UI theme

✔️ Optional Enhancements Implemented

Bookmark / unbookmark articles (stored using localStorage)

Show article highlights

Quick summary pop-ups

Smooth scrolling and article highlighting on open

📁 Project Structure

This project is written entirely in one HTML file, containing:

Section	Description
HTML	Layout, sidebar, article lists, charts, and modal-like summaries
CSS	Teal–green–blue theme, responsive grid, card styles, shadows, buttons
JavaScript	Mock data, filtering, searching, sorting, bookmarking, chart rendering

You can easily break it into multiple files (index.html, styles.css, app.js) if needed.

🚀 How to Run the Project

Download or clone the repository:

git clone https://github.com/your-username/PlanetPulse.git


Open the index.html file directly in any modern browser.

No server setup is required.

The website will load instantly.

Optional: Use VS Code Live Server for auto-reload:

Live Server → Open with Live Server

🖥️ Technologies Used
Technology	Purpose
HTML5	Structure of the web app
CSS3	Styling, layout, gradients, and UI effects
Vanilla JavaScript	Dynamic rendering, filters, bookmarking, mock data
Chart.js	Doughnut chart for category trends
LocalStorage	Bookmark persistence
📊 Features Explained
🔍 Search & Filter

Users can search by keyword (title, summary, category, region).

Sidebar categories allow filtering by topic.

Sorting toggles between newest and oldest articles.

📌 Bookmarking System

Click the ★ icon to save an article.

Saved items appear in the sidebar.

Uses localStorage so bookmarks stay even after refreshing.

📈 Trends Visualization

A doughnut chart displays category distribution.

Auto-updates based on available articles.

🌟 UI Design Choices

Color palette: teal, green, blue for environmental theme

Rounded cards with soft shadows for clean modern look

Responsive grid layout for mobile, tablet, and desktop

Simple modal alternative using JavaScript alerts for summaries (can be upgraded later)

📚 Future Scope

Integrate real-time RSS feeds or News API

Add user authentication

Advanced bookmarking / reading list

Push notifications for breaking environmental news

Commenting and discussion features

Dark mode theme toggle (UI button already present as placeholder)

🧪 Challenges Faced

Designing a clean layout to display large volumes of articles

Keeping the site lightweight even with visual components

Implementing a responsive UI using pure CSS without frameworks

Creating mock data that realistically represents environmental news categories

📷 Screenshots (Optional)

Add screenshots here once the project is deployed or captured:

/screenshots/homepage.png
/screenshots/trends.png
/screenshots/bookmarks.png

📄 License

This project is open-source and available under the MIT License.

🤝 Contributing

Contributions are welcome!
Feel free to fork the repo, make improvements, and submit a pull request.
